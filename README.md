# SMFilter_Experiments

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2529541.svg)](https://doi.org/10.5281/zenodo.2529541)

provides R codes and RMarkdown files for all the experiments in the paper "State-Space Models on Stiefel Manifold with A New Approach to Nonlinear Filtering". The codes and the corresponding RMarkdown were written in November 2018.

Notice that you will have to install the package "SMFilter" before running the RMarkdown code. The package can be found

[SMFilter@CRAN](https://CRAN.R-project.org/package=SMFilter)

or on my GitHub

https://github.com/yukai-yang/SMFilter

How to install the package
--------------------------

You can either install the stable version from CRAN

``` r
install.packages("SMFilter")
```

or install the development version from GitHub

``` r
devtools::install_github("yukai-yang/SMFilter")
```

provided that the package "devtools" has been installed beforehand.

## Simulation.Rmd
The RMarkdown file containing the R code chunks for the experiments.

## Simulation.pdf
The output pdf made by running the RMarkdown code.
