
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

<!-- badges: end -->

The goal of libminer is to provide an overview of your R library setup.
It is a toy package created as a part of a workshop and not meant for
serious use.

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("lgoris/libminer")
```

## Example

To get a count of installed packages in each of your library locations,
optionally with the total sizes, use the `lib_summary()` function:

``` r
library(libminer)
lib_summary()
#>                                                                   Library
#> 1                                      C:/Program Files/R/R-4.4.2/library
#> 2                       C:/Users/ligo9587/AppData/Local/R/win-library/4.4
#> 3 C:/Users/ligo9587/AppData/Local/Temp/Rtmp2nqnOv/temp_libpathb54715616ed
#>   n_packages
#> 1         30
#> 2        169
#> 3          1
# specify `sizes = TRUE` to calculate the total size on disk of your packages
# lib_summary(sizes = TRUE)
```
