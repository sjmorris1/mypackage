
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->

[![R-CMD-check](https://github.com/sjmorris1/mypackage/workflows/R-CMD-check/badge.svg)](https://github.com/sjmorris1/mypackage/actions)
<!-- badges: end -->

The goal of mypackage is to print a personalised greeting from me

## Installation

You can install the devlopment version of mypackage from GitHub with:

``` r
devtools::install_github("sjmorris1/mypackage")
```

## Example

This is a basic example which shows you how to print a generic greeting:

``` r
library(mypackage)
## basic example code
hello()
#> 
#> 
#>  ----- 
#> Hello world from Sam! 
#>  ------ 
#>     \   
#>      \   __
#>    / \
#>    | |
#>    @ @
#>   || ||
#>   || ||
#>   |\_/|
#>   \___/ GB
```

This is a basic example which shows you how to print a personalised
greeting:

``` r
hello(name = "John Smith")
#> 
#>  ----- 
#> Hello John Smith from Sam! 
#>  ------ 
#>     \   
#>      \
#>        '\__
#>       (o )     ___
#>       <>(_)(_)(___)
#>         < < > >
#>         ' ' ` `  [nosig]
#> 
```
