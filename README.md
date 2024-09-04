# VAMPIRE Input files for 1-7 layer MnPS3 ribbons

The repository contains the VAMPIRE input files used for the domain wall motion simulations used in the paper.

Each folder contains the input files for a particular number of layers of a 200 nm x 50 nm MnPS3 ribbon. The folder "dwall_fc" contains the input files to stabilise the initial domain wall with 0 field. In order to reproduce the data from the paper, the user should first run the simulation in "dwall_fc" and then copy the vampire checkpoint files to the folder for the desired field. Then run the simulation in the "timeseries_field_xx" folder which will continue the simulation with the stabilised domain wall and an external field in the z axis now acting on it. Atomic coordinates and spin data is stored every 0.01 ns up till the final time of 2 ns.
