
<!-- README.md is generated from README.Rmd. Please edit that file -->

# cwdata

<!-- badges: start -->

[![R build
status](https://github.com/cgon0007/week7tutorial/workflows/R-CMD-check/badge.svg)](https://github.com/cgon0007/week7tutorial/actions)
<!-- badges: end -->

The goal of cwdata is to …

## Installation

You can install the released version of cwdata from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("cwdata")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("cgon0007/week7tutorial")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(cwdata)
library(tibble)
key_crop_yields
#> # A tibble: 143,825 x 5
#>    country     code   year crop     tonnes_per_hectare
#>    <chr>       <chr> <dbl> <chr>                 <dbl>
#>  1 Afghanistan AFG    1961 wheat                  1.02
#>  2 Afghanistan AFG    1961 rice                   1.52
#>  3 Afghanistan AFG    1961 maize                  1.4 
#>  4 Afghanistan AFG    1961 soybeans              NA   
#>  5 Afghanistan AFG    1961 potatoes               8.67
#>  6 Afghanistan AFG    1961 beans                 NA   
#>  7 Afghanistan AFG    1961 peas                  NA   
#>  8 Afghanistan AFG    1961 cassava               NA   
#>  9 Afghanistan AFG    1961 barley                 1.08
#> 10 Afghanistan AFG    1961 cocoa                 NA   
#> # … with 143,815 more rows
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub\!
