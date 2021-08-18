# evobee-data

This repository contains configuration files and output data logs for various experiments conducted with the [EvoBee](https://github.com/tim-taylor/evobee) software.

The following table lists the folders you will find here and a description of their contents.

| folder | description |
| ------ | ----------- |
| patchiness-constancy-paper | Files associated with our experiments on patchiness and constancy, reported in a paper currently under review (August 2021)|
| theor-ecol-2020 | Files associated with the experiments reported in A. Dorin, T. Taylor, M. Burd, J. Garcia, M. Shrestha, A. G. Dyer. ***Competition and pollen wars: simulations reveal the dynamics of competition mediated through heterospecific pollen transfer by non-flower constant insects*** Theoretical Ecology, 13, 2020|

## Format of data files

The folders in this repository contain raw output files for each individual run of the
simulation described in one of our papers.

There are three output files associated with each run:

| filename | description |
| -------- | ----------- |
|[runname]-[timestamp]-[uid]-config.json|The simulation configuration file used for this run. The format of this file is described [here](https://tim-taylor.github.io/evobee/evobee-config.html).|
|[runname]-[timestamp]-[uid]-info.txt|Contains information about the specific version of the simulation program used for this run.|
|[runname]-[timestamp]-[uid]-log.txt|The output log from the run. The format of each line depends upon which log flags are specified in the simulation configuration file. Details of the different formats can be found [here](https://tim-taylor.github.io/evobee/evobee-config.html).|
