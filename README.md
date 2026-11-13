# iRafNet

Integrative random forest inference of gene regulatory networks that combines expression data with prior information such as protein-protein interactions.

Compatibility updates by Renova.

Version 1.1.1.9001 replaces the deprecated `Calloc` and `Free` memory macros in the C random-forest code with `R_Calloc` and `R_Free`. No R function was changed.

## Install

```r
install.packages("iRafNet", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/iRafNet@renova-1.1.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

iRafNet is by Francesca Petralia (maintainer), Pei Wang, Zhidong Tu and Jialiang Yang, with contributions from Adele Cutler, Leo Breiman, Andy Liaw and Matthew Wiener; the original CRAN package is at <https://CRAN.R-project.org/package=iRafNet>. The C sources keep the Breiman, Cutler and Merck & Co. copyright and GPL notices. License: GPL (>= 2); see [COPYING](COPYING).
