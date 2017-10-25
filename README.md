
<!-- README.md is generated from README.Rmd. Please edit that file -->
Yang2013data
============

This is a data package for running with the QTLseqr vignette. Please read the vignette [here](https://drive.google.com/file/d/0B3wMyxzoUzkVOFFmN1VtZjdlV28/view?usp=sharing)

For more information on running QTLseqr go to: <https://github.com/bmansfeld/QTLseqr>

Installation
------------

You can install Yang2013data from github with:

``` r
# install.packages("devtools")
devtools::install_github("bmansfeld/Yang2013data")
```

Loading the data
----------------

``` r
library("Yang2013data")

rawData <- system.file(
  "extdata", 
  "Yang_et_al_2013.table",
  package = "Yang2013data",
  mustWork = TRUE)
```
