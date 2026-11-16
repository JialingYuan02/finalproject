# finalproject

Jialing Yuan’s final project for BST 260, Fall 2026.

This R package contains public health datasets and their documentation.
The project website is at
<https://jialingyuan02.github.io/finalproject/>.

## Installation

``` r
devtools::install_github("JialingYuan02/finalproject")
```

## Data

The package includes `waterborne`, `cdcmurd`, `cdcfiremort`, and
`gunleg`. Their help pages document the original data sources.

``` r
data("waterborne", package="finalproject")
waterborne[[1]]
```

This project is based on Vincent Carey’s [BST 260 project
template](https://github.com/vjcitn/bst260project-template). The
original [course
instructions](https://jialingyuan02.github.io/finalproject/articles/instructions.md)
and [project
suggestions](https://jialingyuan02.github.io/finalproject/articles/stubs.md)
are included for reference.
