
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sgs

<!-- badges: start -->

[![Build
Status](https://travis-ci.com/litos81/sgs.svg?branch=master)](https://travis-ci.com/litos81/sgs)
[![codecov](https://codecov.io/gh/litos81/sgs/branch/master/graph/badge.svg?token=Qd5gkpnxFc)](https://codecov.io/gh/litos81/sgs)
[![Latest
release](https://img.shields.io/github/release/litos81/sgs.svg)](https://github.com/litos81/sgs/releases)
[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)
<!-- badges: end -->

The goal of sgs is to provide a set of methods to transform ETRS89 (2D)
coordinates to the equivalent OSGB36 National Grid coordinates, and
vice-versa, using [Ordnance Survey’s National Grid Transformation
OSTN15](https://www.ordnancesurvey.co.uk/blog/2016/09/ostn15-new-geoid-britain/).

The Coordinate Systems supported by `sgs` are: \* EPSG:4326 \* EPSG:4258
\* EPSG:27700 \* EPSG:3857 \* EPSG:4277

Additionally it also contains several methods wrapping `sf` functions
that make certain actions easier when using gis in TERR/Open Source R
within ‘TIBCO Spotfire’.

## Installation

You can install the released version of sgs from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("sgs")
```

**Note:** To use only the OSTN15 transformations there is no need to
install the package’s dependencies.

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
