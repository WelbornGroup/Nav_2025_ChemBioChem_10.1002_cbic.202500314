This repository contains the input files used for AMOEBA simulations for our paper "Preorganized Electric Fields in Voltage-Gated Sodium Channels", doi: 10.1002/cbic.202500314.
Each folder contains the input structure in both .pdb and .xyz (Tinker input) formats, the tinker .key files that controls the simulation setup, and the Tinker parameter file (.prm) for AMOEBA force field parameters containing POPE membrane. 

The trajectories used in our paper are available for download on zenodo, the doi for the trajectories are:  
10.5281/zenodo.15425776  
10.5281/zenodo.15464312  
10.5281/zenodo.15467504  
10.5281/zenodo.15467641  
10.5281/zenodo.15477120  
10.5281/zenodo.15491750  
10.5281/zenodo.15491752  
10.5281/zenodo.15498605  
10.5281/zenodo.15473080  
10.5281/zenodo.15477118  
10.5281/zenodo.15490901  

For the deposits of CHARMM simulations with GROMACS, the topology and force field parameters for each simulation are included in ```toppar``` folder, the initial structure for the simulation is ```step5_input.pdb```. ```step6.0*``` to ```step7*``` are the simulation setup for minimization, equilibration and production. The trajectories for minimization, NVT equilibration, NPT equilibration, and production are ```em.trr```, ```nvt*.trr```, ```npt*.trr```, and ```md1.trr```, respectively. The energy files and log files for each have the same file name with file extenion of ```.edr``` and ```.log```, respectively.
