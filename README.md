
<!-- README.md is generated from README.Rmd. Please edit that file -->

# hello

<!-- badges: start -->
<!-- badges: end -->

A set of functions to be polite with our colleagues and friends.

## Installation

You can install the development version of hello like so:

``` r
remotes::install_github("statnmap/hello")
remotes::install_gitlab("statnmap/hello")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(hello)
## basic example code
```

# Say hello to someone

You can say hello to someone in particular using `say_hello()`.

``` r
say_hello() # Hello Berra
#> Hello Berra
say_hello(someone = "Seb") # Hello Seb
#> Hello Seb

hello_anna <- say_hello(someone = "Anna") 
#> Hello Anna
hello_anna
#> NULL
# library(ggplot2)
# ggplot() + geom_point()
```

## Code of Conduct

Please note that the hello project is released with a [Contributor Code
of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
