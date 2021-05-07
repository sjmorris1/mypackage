
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->
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
#>  ----- 
#> Hello world from Sam! 
#>  ------ 
#>     \   
#>      \
#>               |
#>               |
#>               |
#>              __
#>           | /  \ |
#>          \_\\  //_/
#>           .'/()\'.
#>            \\  //  [nosig]
#> 
```

This is a basic example which shows you how to print a personalised
greeting:

``` r
hello(name = "John Smith")
#> 
#>  -------------- 
#> Hello John Smith from Sam! 
#>  --------------
#>     \
#>       \
#>         \
#>         /\_/\         _
#>        /``   \       / )
#>        |n n   |__   ( (
#>       =(Y =.‛`   `\  \ \
#>       {`"`        \  ) )
#>       {       /    |/ /
#>        \\   ,(     / /
#>         ) ) /-‛\  ,_.‛
#>   jgs  (,(,/ ((,,/
#> 
```
