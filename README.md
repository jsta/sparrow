
<!-- README.md is generated from README.Rmd. Please edit that file -->
sparrow
=======

This package currently serves only the 1992 National Scale Phosphorus Model.

Installation
------------

You can install sparrow from github with:

``` r
# install.packages("devtools")
devtools::install_github("jsta/sparrow")
```

Data
----

GIS data can be obtained automatically with the `erf_get` function. Phosphorus data must be obtained manually and placed at `sparrow:::cache_path()` before running `p_get` (until the SPARROW decision support system is made available again).
