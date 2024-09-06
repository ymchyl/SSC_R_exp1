
<!-- README.md is generated from README.Rmd. Please edit that file -->

# SCCTempConverter

<!-- badges: start -->
<!-- badges: end -->

The goal of SCCTempConverter is to …

## Installation

You can install the development version of SCCTempConverter from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("ymchyl/SSC_R_exp1")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
devtools::install_github("ymchyl/SSC_R_exp1")
#> Using GitHub PAT from the git credential store.
#> Downloading GitHub repo ymchyl/SSC_R_exp1@HEAD
#> ── R CMD build ─────────────────────────────────────────────────────────────────
#>      checking for file ‘/private/var/folders/f_/lcww9q890r5c9jr1zmkp2d900000gr/T/RtmpIZn80X/remotes1596331d1c4f4/ymchyl-SSC_R_exp1-0d9675c/DESCRIPTION’ ...  ✔  checking for file ‘/private/var/folders/f_/lcww9q890r5c9jr1zmkp2d900000gr/T/RtmpIZn80X/remotes1596331d1c4f4/ymchyl-SSC_R_exp1-0d9675c/DESCRIPTION’
#>   ─  preparing ‘SCCTempConverter’:
#>      checking DESCRIPTION meta-information ...  ✔  checking DESCRIPTION meta-information
#>   ─  checking for LF line-endings in source and make files and shell scripts
#>   ─  checking for empty or unneeded directories
#>   ─  building ‘SCCTempConverter_0.0.1.0.tar.gz’
#>      
#> 
library(SCCTempConverter)
```

### run examples to see how function works

``` r
## basic example code
F_to_C(30);
#> [1] -1.111111

C_to_F(20)
#> [1] 68
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
up-to-date. `devtools::build_readme()` is handy for this.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
