
<!-- README.md is generated from README.Rmd. Please edit that file -->
praiseme
========

The goal of praiseme is to praise people.

Installation
------------

You can install praiseme from github with:

``` r
# install.packages("devtools")
devtools::install_github("leeshdiz/praiseme")
```

Example
-------

This is an example of how you can use praise to praise either Alicia (default), or someone else

``` r
library(praiseme)

# Just Alicia
praise()
#> [1] "You're the best, Alicia!"

# Or a friend
praise("Quintin")
#> [1] "You're the best, Quintin!"
```
