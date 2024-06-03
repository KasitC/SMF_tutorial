# Single-molecule footprinting (SMF) data analysis tutorial
This github repository contains example data sets and scripts for performing SMF data analysis. <br />
The examples include some basic QCs of methylation footprinting, plottings, and single-molecule state frequency analysis.


# Installation
This tutorial requires several functions from _SingleMoleculeFootprinting_ R package (promoter branch).
To install _SingleMoleculeFootprinting_, execute the following
```r
remotes::install_github(repo = "https://github.com/Krebslabrep/SingleMoleculeFootprinting.git", ref = "promoter", build_vignettes = FALSE)
```
In addition, please also make sure that the following packages have already been installed. <br />
- `tidyverse` <br />
- `ggplot2` <br />
- `here` <br />
- `GGally` <br />
- `QuasR` <br />
- `BSgenome.Dmelanogaster.UCSC.dm6` <br />

Please note that the scripts were created and tested in `R 4.2.2` environment.

