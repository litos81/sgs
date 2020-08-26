
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sgs - Simple GIS (with OSGB)

<!-- badges: start -->

[![Build
Status](https://travis-ci.com/litos81/sgs.svg?branch=master)](https://travis-ci.com/litos81/sgs)
[![codecov](https://codecov.io/gh/litos81/sgs/branch/master/graph/badge.svg?token=Qd5gkpnxFc)](https://codecov.io/gh/litos81/sgs)
[![Latest
release](https://img.shields.io/github/release/litos81/sgs.svg)](https://github.com/litos81/sgs/releases)
[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)
<!-- badges: end -->

The goal of sgs is to provide a set of methods to transform ETRS89
coordinates to the equivalent OSGB36 National Grid coordinates, and
vice-versa, using [Ordnance Survey’s National Grid Transformation
OSTN15](https://www.ordnancesurvey.co.uk/blog/2016/09/ostn15-new-geoid-britain/).

The Coordinate Systems supported by `sgs` are:

  - ETRS89: EPSGs 4258, 4937, 4936 (and 3857)
  - WGS84: EPSGs 4326, 4979, 4978
  - OSGB36: EPSGs 27700, 7405, 4277

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
