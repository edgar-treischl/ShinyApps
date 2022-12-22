
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Shinyapps

<!-- badges: start -->

[![R-CMD-check](https://github.com/edgar-treischl/shinyapps/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/edgar-treischl/shinyapps/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

This package is the home for shiny apps and installs all necessary
packages to run them.

## Installation

You can install the development version of ShinyApps from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("edgar-treischl/ShinyApps")
```

Use the `run_app()` function to run one of the shiny apps on your
computer.

``` r
shinyapps::run_app()
#> Error: Please run `run_app()` with a valid name as an argument.
#> Valid examples are: 'causality', 'power', 'titanic'
```
