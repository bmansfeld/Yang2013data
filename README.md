
<!-- README.md is generated from README.Rmd. Please edit that file -->
Yang2013data
============

This is a data package for running with the QTLseqr vignette. Please read the vignette [here](https://drive.google.com/file/d/0B3wMyxzoUzkVOFFmN1VtZjdlV28/view?usp=sharing)

For more information on running QTLseqr go to: <https://github.com/bmansfeld/QTLseqr>

he data is derived from: Mapping of Quantitative Trait Loci Underlying Cold Tolerance in Rice Seedlings via High-Throughput Sequencing of Pooled Extremes. Yang Z, Huang D, Tang W, Zheng Y, Liang K, et al. (**2013**) PLOS ONE 8(7): e68433. <https://doi.org/10.1371/journal.pone.0068433>

Raw reads were downloaded from the NCBI Short Read Archive, aligned to the v7 Nipponbare genome (<http://rice.plantbiology.msu.edu/>) and SNPs were called as described in the GATK “Best Practices” (<https://software.broadinstitute.org/gatk/best-practices/>).

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
