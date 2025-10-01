# How test cases may affect response variable measurement in TDD experiments: an empirical study

This file describes how to reproduce the results shown in the article.

## Figures and Tables

The repository contains a mix of `.tex` and `.Rtex` files, as well as other files necessary for the proper generation of the article.

The `.Rtex` files contain LaTeX code (just like the `.tex` files) but, additionally, also include embedded R code used with [knitr](https://yihui.org/knitr/).

The R code can be run directly using an appropriate interpreter, such as [RStudio](https://posit.co/download/rstudio-desktop/), or compiled directly using R, RStudio, or [Overleaf](https://www.overleaf.com/). For the correct execution of the R code, the researcher must set the repository root as the working directory, since the experimental data are stored in the `data/` and `calculation_of_deviations/` directories. The names and types of the data files are explicitly indicated in the R code.

## Figures in Section VII

The figures in Section VII are derived from data generated using reference code for the BSK and MR tasks, and also the AH and EP test suites. The `calculation_of_deviations/` directory contains both the data and the Java code that generates them. The `calculation_of_deviations/` directory contains an [Eclipse](https://www.eclipse.org) workspace, so it can be opened directly using that tool. Minor adjustments may be necessary to run the code, such as specifying the particular JRE installed on the researcher’s machine who wishes to reproduce the results.

## Test Suites

The test suites are available in the `test_suites/` directory (as well as in the `calculation_of_deviations/` directory).
