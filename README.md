
<!-- README.md is generated from README.Rmd. Please edit that file -->

# forcis <img src="man/figures/logo.png" height="120px" align="right" style="float:right; height:120px;"/>

<!-- badges: start -->

[![R CMD
Check](https://github.com/FRBCesab/forcis/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/FRBCesab/forcis/actions/workflows/R-CMD-check.yaml)
[![Website
deployment](https://github.com/FRBCesab/forcis/actions/workflows/pkgdown.yaml/badge.svg)](https://github.com/FRBCesab/forcis/actions/workflows/pkgdown.yaml)
[![Test
coverage](https://github.com/ahasverus/forcis/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/ahasverus/forcis/actions/workflows/test-coverage.yaml)
[![CRAN
status](https://www.r-pkg.org/badges/version/forcis)](https://CRAN.R-project.org/package=forcis)
[![License: GPL (\>=
2)](https://img.shields.io/badge/License-GPL%20%28%3E%3D%202%29-blue.svg)](https://choosealicense.com/licenses/gpl-2.0/)
<!-- badges: end -->

## Table of contents

<p align="left">
• <a href="#overview">Overview</a><br> •
<a href="#features">Features</a><br> •
<a href="#installation">Installation</a><br> •
<a href="#get-started">Get started</a><br> •
<a href="#long-form-documentations">Long-form documentations</a><br> •
<a href="#citation">Citation</a><br> •
<a href="#contributing">Contributing</a><br> •
<a href="#acknowledgments">Acknowledgments</a><br> •
<a href="#references">References</a>
</p>

## Overview

The goal of the R package `forcis` is to provide an interface to the
[FORCIS database](https://zenodo.org/doi/10.5281/zenodo.7390791) on
global foraminifera distribution (Chaabane *et al.* 2023). This package
allows to download, handle, homogenize and visualize FORCIS data.

## Features

The main purpose of `forcis` is to…

****LIST HERE THE MAIN FEATURES****

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
## Install < remotes > package (if not already installed) ----
if (!requireNamespace("remotes", quietly = TRUE)) {
  install.packages("remotes")
}

## Install dev version of < forcis > from GitHub ----
remotes::install_github("FRBCesab/forcis")
```

Then you can attach the package `forcis`:

``` r
library("forcis")
```

**N.B.** The `forcis` package requires at least the version of **4.1.0
of R**. Please update R if you are using an older version.

## Get started

For an overview of the main features of `forcis`, please read the [Get
started](https://frbcesab.github.io/forcis/articles/forcis.html)
vignette.

## Long-form documentations

Additional vignettes will be available soon.

## Citation

Please cite this package as:

> Casajus N, Greco M, Giraud X & Chaabane S (2024) forcis: An R client
> to access the FORCIS database. R package version 0.0.0.9000. URL:
> <https://frbcesab.github.io/forcis/>.

You can also run:

``` r
citation("forcis")
```

## Contributing

All types of contributions are encouraged and valued. For more
information, check out our [Contributor
Guidelines](https://github.com/FRBCesab/forcis/blob/main/CONTRIBUTING.md).

Please note that the `forcis` project is released with a [Contributor
Code of
Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

## Acknowledgments

This package has been developed for the
[FRB-CESAB](https://www.fondationbiodiversite.fr/en/about-the-foundation/le-cesab/)
working group
[FORCIS](https://www.fondationbiodiversite.fr/en/the-frb-in-action/programs-and-projects/le-cesab/forcis/)
that aims to understand the importance of the main stressors such as
temperature and ocean acidification that govern foraminifera species
distribution and calcification processes, with focus on present and
near-future ocean impacts.

We want to thanks Khalil Hammami
([@khammami](https://github.com/khammami)) for his valuable contribution
to this package.

## References

Chaabane S, De Garidel-Thoron T, Giraud X, Schiebel R, Beaugrand G,
Brummer G-J, Casajus N, Greco M, Grigoratou M, Howa H, Jonkers L, Kucera
M, Kuroyanagi A, Meilland J, Monteiro F, Mortyn G, Almogi-Labin A, Asahi
H, Avnaim-Katav S, Bassinot F, Davis CV, Field DB, Hernández-Almeida I,
Herut B, Hosie G, Howard W, Jentzen A, Johns DG, Keigwin L, Kitchener J,
Kohfeld KE, Lessa DVO, Manno C, Marchant M, Ofstad S, Ortiz JD, Post A,
Rigual-Hernandez A, Rillo MC, Robinson K, Sagawa T, Sierro F, Takahashi
KT, Torfstein A, Venancio I, Yamasaki M & Ziveri P (2023) The FORCIS
database: A global census of planktonic Foraminifera from ocean waters.
**Scientific Data**, 10, 354. DOI:
[10.1038/s41597-023-02264-2](https://doi.org/10.1038/s41597-023-02264-2).
