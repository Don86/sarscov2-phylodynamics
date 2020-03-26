# Overview

* Visualization of the phylogenetics of SARS-COV-2, or covid19. Quite similar to the current visualization over at nextStrain.org.
* Hoping to slap on Kuhnert et. al's [BDSIR](https://royalsocietypublishing.org/doi/full/10.1098/rsif.2013.1106) model to estimate phylodynamic trajectories

### Details

* Data obtained (manually) from GISAID
* Aligned with `MAFFT` and checked with `Tempest`
* Initial tree computed using `FastTree`
* Timed tree computed using the `treetime` webserver, which is presumably faster than my laptop
