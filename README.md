extraInserts
================

[![Build
Status](https://travis-ci.org/konradzdeb/extraInserts.svg?branch=master)](https://travis-ci.org/konradzdeb/extraInserts)

## Description

The purpose of this trivial package is to offer a set of convenience
functions inserting various (pipe) operators so those can be
conveniently linked to keyboard shortcuts in
[RStudio](https://www.rstudio.com/products/RStudio/).

This package was developed for fun and to conveniently transport
frequently used functions across environments.

### Available operators

|  Operator  | Description                                                                                                          |
| :--------: | :------------------------------------------------------------------------------------------------------------------- |
|  **`->`**  | Rightwards form of the [common assignment operator](https://rdrr.io/r/base/assignOps.html)                           |
| **`%<>%`** | The *compound assignment pipe-operator* offered in the excellent [magrittr](https://magrittr.tidyverse.org/) package |
| **`%T>%`** | The *tee operator* from the [magrittr](https://magrittr.tidyverse.org/) package                                      |
| **`%$%`**  | The *exposition pipe-operator* from the [magrittr](https://magrittr.tidyverse.org/) package                          |

## Installation

``` r
if (!requireNamespace("remotes", quietly = TRUE)) {
  install.packages("remotes")
}
remotes::install_github('konradedgar/extraInserts')
```
