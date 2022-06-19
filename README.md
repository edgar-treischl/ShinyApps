
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Graphs

<!-- badges: start -->
<!-- badges: end -->

This site is the home, a personal package, and a vehicle for graphs made
with R. It installs the source code of illustrations and other graphs
that I made and provides convenient functions to make graphs with
`ggplot2` (e.g. slope plots.)

## Installation

You can install Graphs from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("edgar-treischl/Graphs")
```

## Example

Without input, the `plotgraph()` function returns all available graphs.

``` r
library(shinyapps)
```

The `plotgraph()` function just picks the installed source code and
returns the graphs. For example, the `datasaurus` plot.

``` r
## basic example code
plotgraph("datasaurus.R")
```

<img src="man/figures/README-unnamed-chunk-2-1.png" width="100%" />

And the package gives access to convenient functions to make `ggplot2`
graphs with less effort. For example, `ggslope()` returns a slope chart.
