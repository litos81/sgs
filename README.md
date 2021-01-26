sgs - Simple GIS (with OSGB)
================

<!-- README.md is generated from README.Rmd. Please edit that file -->

<!-- badges: start -->

[![R-CMD-check](https://github.com/litos81/sgs/workflows/R-CMD-check/badge.svg?branch=master)](https://github.com/litos81/sgs/actions?workflow=R-CMD-check)
[![codecov](https://codecov.io/gh/litos81/sgs/branch/master/graph/badge.svg?token=Qd5gkpnxFc)](https://codecov.io/gh/litos81/sgs?branch=master)
[![Latest
release](https://img.shields.io/github/release/litos81/sgs.svg)](https://github.com/litos81/sgs/releases)
[![license](https://img.shields.io/badge/license-BSD%202--Clause-green.svg)](https://opensource.org/licenses/BSD-2-Clause)
<!-- badges: end --> (DO NOT USE… YET)

The goal of sgs is to provide a set of methods to transform ETRS89
coordinates to the equivalent OSGB36 National Grid coordinates, and
vice-versa, using [Ordnance Survey’s National Grid Transformation
OSTN15](https://www.ordnancesurvey.co.uk/blog/2016/09/ostn15-new-geoid-britain/).

The Coordinate Systems supported by `sgs` are:

  - ETRS89: EPSGs 4258, 4937, 4936 and 3035
  - WGS84: EPSGs 4326, 4979, 4978 and 3857
  - OSGB36: EPSGs 27700, 7405 and 4277

## Installation

You can install the released version of sgs from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("sgs")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("litos81/sgs")
```

## Example

Example 1:

``` r
library(sgs)
## basic example code
```

Example 2:

``` r
library(sgs)
## basic example code
```
