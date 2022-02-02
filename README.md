# TubulinNCs

This repository contains the set of data shown in the paper "Reconstitution of microtubule into GTP-responsive nanocapsules".

All the input data needed to run the simulations and get the results are organized in 4 different folders:

 * `00-MDPFiles/`

  in this folder there are the mdp files for each step for Gromacs-MD simulations:energy minimization, nvt, npt, production with restraints and production without restraints.

 * `01-TubulinSystems-Topologies/`

  the folder contains the atomistic topologies for the tubulin assembly with and without glue (`SystemA_Glue/`, `SystemA_noGlue/`, `SystemB_Glue/`, `SystemB_noGlue/`).

 * `02-TubulinSystems-Minimized/`

  in this folder there are the system minimized systems (`SystemA_Glue/`, `SystemA_noGlue/`, `SystemB_Glue/`, `SystemB_noGlue/`).

 * `03-OnlyGlue-Minimized/` 

  the folder contains the atomistic model of the glue and its topology files.
