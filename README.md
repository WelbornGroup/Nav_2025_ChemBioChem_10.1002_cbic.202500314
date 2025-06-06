This repository contains the input files used for AMOEBA simulations for our paper "Preorganized Electric Fields in Voltage-Gated Sodium Channels", doi: 10.1002/cbic.202500314.
Each folder contains the input structure in both .pdb and .xyz (Tinker input) formats, the tinker .key files that controls the simulation setup, and the Tinker parameter file (.prm) for AMOEBA force field parameters containing POPE membrane. 

The trajectories used in our paper are available for download on zenodo, the doi for the trajectories are:  
Nav1.5 CHARMM: 10.5281/zenodo.15425777 (https://zenodo.org/records/15425777)  
Nav1.7 CHARMM: 10.5281/zenodo.15464313 (https://zenodo.org/records/15464313)  
Nav1.5 AMOEBA Conform 1: 10.5281/zenodo.15467505 (https://zenodo.org/uploads/15467505)  
Nav1.5 AMOEBA Conform 2: 10.5281/zenodo.15467642 (https://zenodo.org/records/15467642)  
Nav1.5 AMOEBA Conform 3: 10.5281/zenodo.15477121 (https://zenodo.org/records/15477121)  
Nav1.6 AMOEBA Conform 1: 10.5281/zenodo.15491751 (https://zenodo.org/records/15491751)  
Nav1.6 AMOEBA Conform 2: 10.5281/zenodo.15491753 (https://zenodo.org/records/15491753)  
Nav1.6 AMOEBA Conform 3: 10.5281/zenodo.15498606 (https://zenodo.org/records/15498606)  
Nav1.7 AMOEBA Conform 1: 10.5281/zenodo.15473081 (https://zenodo.org/records/15473081)  
Nav1.7 AMOEBA Conform 2: 10.5281/zenodo.15477119 (https://zenodo.org/records/15477119)  
Nav1.7 AMOEBA Conform 3: 10.5281/zenodo.15490902 (https://zenodo.org/records/15490902)  

For the deposits of CHARMM simulations with GROMACS, the topology and force field parameters for each simulation are included in ```toppar``` folder, the initial structure for the simulation is ```step5_input.pdb```. ```step6.0*``` to ```step7*``` are the simulation setup for minimization, equilibration and production. The trajectories for minimization, NVT equilibration, NPT equilibration, and production are ```em.trr```, ```nvt*.trr```, ```npt*.trr```, and ```md1.trr```, respectively. The energy files and log files for each have the same file name with file extenion of ```.edr``` and ```.log```, respectively.
