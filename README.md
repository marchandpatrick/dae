# dae

[![Project Status: Active:  The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![minimal R version](https://img.shields.io/badge/R%3E%3D-2.10.0-6666ff.svg)](https://cran.r-project.org/)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/dae)](https://cran.r-project.org/package=dae)
[![packageversion](https://img.shields.io/badge/Package%20version-3.0--31-orange.svg?style=flat-square)](/commits/master)
[![Last-changedate](https://img.shields.io/badge/last%20change-2019--04--03-yellowgreen.svg)](/commits/master)
[![Licence](https://img.shields.io/badge/license-GPL%20(%3E%3D2)-green.svg)](http://choosealicense.com/licenses/gpl-2.0/)
[![Downloads](https://cranlogs.r-pkg.org/badges/last-week/dae)](commits/master)


`dae` is an R package that collects together functions that are useful in the design and ANOVA of experiments. It is stronger in functions to aid in the design of experiments, having functions that facilitate factor manipulation, randomizing designs and assessing the properties of designs.

## More information

For more information install the package and run the R command `news(package = “dae”)` or consult the [manual](./vignettes/dae-manual.pdf). 

An overview can be obtained using `?dae`. 

## Installing the package

### From a repository using `drat`

Windows binaries and source tarballs of the latest version of `dae` are available for installation from my [repository](http://chris.brien.name/rpackages). Installation instructions are available there.

### Directly from  GitHub

`dae` is an R package available on GitHub, so it can be installed from the RStudio console or an R command line session using the `devtools` command `install_github`. First, make sure `devtools` is installed, which, if you do not have it, can be done as follows:

`install.packages("devtools")`

Next, install `dae` from GitHub by entering:

`devtools::install_github("briencj/dae")`.

Version 2.0-12 of the package is available from CRAN so that you could first install it and its dependencies using:

`install.packages("dae")`


If you have not previously installed `dae` then you will need to install it dependencies:

`install.packages(c("ggplot2", "plyr")))`

## What is does

It is described in the manual, which can be found using `vignette("Manual", package = "dae")`. Also found using `vignette("DesignNotes", package = "dae")` is a vignette describing how to use `designRandomize` to produce randomized layouts for experiments and `designAnatomy` to assessing the properties of designs. It covers both standard and multiphase experimental designs. The data sets that go with the vignette are available in `dae`.

The content falls into the following natural groupings: 

(i) Data 

(ii) Factor manipulation functions

(iii) Design functions

(iv) ANOVA functions

(v) Matrix functions

(vi) Projector and canonical efficiency functions

(vii) Miscellaneous functions.

## What it needs  
  
It imports `ggplot2`, `graphics`, `methods`, [plyr](<https://CRAN.R-project.org/package=plyr>), `stats`.

## License

The `dae` package is distributed under the [GPL (>= 2) licence](<https://opensource.org/licenses/GPL-2.0>).
