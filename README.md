# Patterns
A collection of data acquisition and analysis tools for experimental data on pattern forming particles in oscillating flows.

Organisational additions such as creation of subdirectories or changing file dependencies will be done from the 'organisation' branch.

Data used for example or validation purposes is stored in the 'data' directory. Analysis scripts will be created and developed in the 'analysis/validation' directory. Once a working version is obtained it will be copied/adapted/transfered to 'analysis/final'.

## An important note about jupyter notebooks
All commits should contain no 'output' cells in order to keep only the meaningfull changes in the scripts. This is easiest achieved by restarting the kernel and 'Clear All Outputs'. Alternatively, only the lines with the relevant changes can be added the commit. 
Pull requests with output in the jupyter notebooks will not be accepted.
