############################################################################################################################
This folder contains input files for running biased (qmmm-qmbox20A-metaD-withd3.inp) density functional theory (DFT) quantum mechanics (QM)/ molecular mechanics (MM) molecular dynamics (MD) simulations with cp2k for the succinimide formation in MjGATase.

AMBER parameter and pdb file are located in the folder "topology". The provided pdb contains the reactant state (109th residue as N) of the protein in the water box with charge neutralizing Na+ ions. 

The basis set files used are in the folder "basisset". 

Before the production run (reactionRun folder) the system has been equilibrated in three steps using mechanical embedding and electrostatic embedding. The corresponding input files are kept in the folder "equilibration" and should be run sequentially (1.em-me_pbe.inp, 2.em-ee_pbe.inp, 3.nvt-ee_gpw_pbe.inp).

