
<!-- README.md is generated from README.Rmd. Please edit that file -->

# SANba v0.1.0

<!-- badges: start -->

[![R-CMD-check](https://github.com/fradenti/SANba/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/fradenti/SANba/actions/workflows/R-CMD-check.yaml)
[![Last
Commit](https://img.shields.io/github/last-commit/fradenti/SANvi)](https://github.com/fradenti/SANvi)
<!-- badges: end -->

SANba is a meta-package for the Bayesian analysis of grouped data using
shared atoms nested models. It encompasses both `SANple` and `SANvi`.
The former package can be used to estimate nested models with MCMC, the
second implements variational inference methods.

## Installation

You can install the development version of SANba like so:

``` r
remotes::install_github("fradent/SANba")
```

## Load both `SANple` and `SANvi`

``` r
library(SANba)
#> ── Attaching packages ─────────────────────────────────────────── SANba 0.0.1 ──
#> ✔ SANvi  0.1.0     ✔ SANple 0.0.1
```

For more information, see

- the [SANple repo](https://github.com/laura-dangelo/SANple)
- the [SANple
  package](https://cran.r-project.org/web/packages/SANple/index.html)  
- the [SANvi repo](https://github.com/fradenti/SANvi)  
- the [SANvi
  package](https://cran.r-project.org/web/packages/SANvi/index.html)
