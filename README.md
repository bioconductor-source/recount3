
<!-- README.md is generated from README.Rmd. Please edit that file -->

# recount3 <img src="man/figures/logo.png" align="right" width="400px" />

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![BioC
status](http://www.bioconductor.org/shields/build/release/bioc/recount3.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/recount3)
[![Codecov test
coverage](https://codecov.io/gh/LieberInstitute/recount3/branch/master/graph/badge.svg)](https://codecov.io/gh/LieberInstitute/recount3?branch=master)
[![R build
status](https://github.com/LieberInstitute/recount3/workflows/R-CMD-check/badge.svg)](https://github.com/LieberInstitute/recount3/actions)
[![Test
coverage](https://github.com/LieberInstitute/recount3/workflows/test-coverage/badge.svg)](https://github.com/LieberInstitute/recount3/actions)
[![Pkgdown
deployment](https://github.com/LieberInstitute/recount3/workflows/pkgdown/badge.svg)](https://github.com/LieberInstitute/recount3/actions)
<!-- badges: end -->

Explore and download data from the recount project available at the
[recount3 website](https://jhubiostatistics.shinyapps.io/recount3/).
Using the `recount3` package you can download
*RangedSummarizedExperiment* objects at the gene, exon or exon-exon
junctions level, the raw counts, the phenotype metadata used, the urls
to the sample coverage bigWig files or the mean coverage bigWig file for
a particular study. The *RangedSummarizedExperiment* objects can be used
by different packages for performing differential expression analysis.
Using [derfinder](http://bioconductor.org/packages/derfinder) you can
perform annotation-agnostic differential expression analyses with the
data from the recount project.

For more information about `recount3` check the vignettes [through
Bioconductor](http://bioconductor.org/packages/recount3) or at the
[documentation website](http://lieberinstitute.github.io/recount3).

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install `recount3` using from
[Bioconductor](http://bioconductor.org/) the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("recount3")
```

## Citation

Below is the citation output from using `citation('recount3')` in R.
Please run this yourself to check for any updates on how to cite
**recount3**.

``` r
citation('recount3')
```

Please note that the `recount3` was only made possible thanks to many
other R and bioinformatics software authors. We have cited their work
either in the pre-print or the vignette of the R package.

## Code of conduct

Please note that the `recount3` project is released with a [Contributor
Code of Conduct](CODE_OF_CONDUCT.md). By contributing to this project,
you agree to abide by its terms.

## Development tools

  - Testing on Bioc-devel is possible thanks to [R
    Travis](http://docs.travis-ci.com/user/languages/r/) and [GitHub
    actions through
    `usethis`](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/).
  - Code coverage assessment is possible thanks to
    [codecov](https://codecov.io/gh).
  - The [documentation
    website](http://lieberinstitute.github.io/recount3) is automatically
    updated thanks to
    *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.

## Teams involved

  - [Ben Langmead’s lab at JHU Computer
    Science](http://www.langmead-lab.org/),
  - [Kasper Daniel Hansen’s lab at JHBSPH Biostatistics
    Department](https://www.hansenlab.org/),
  - [Leonardo Collado-Torres](http://lcolladotor.github.io/) and [Andrew
    E. Jaffe](http://aejaffe.com/) from [LIBD](https://www.libd.org/),
  - [Abhinav Nellore’s lab at OHSU](http://nellore.bio/),
  - Data hosted by [SciServer at JHU](https://www.sciserver.org/).

|                                                                                                                                                                               |                                                                                                      |                                                                                                                                                                         |                                                                                                                                                   |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="http://www.langmead-lab.org/"><img src="http://www.langmead-lab.org/wp-content/uploads/2014/01/Screen-Shot-2014-02-02-at-5.20.13-PM-1024x199.png" width="250px"></a> | <a href="https://www.libd.org/"><img src="http://aejaffe.com/media/LIBD_logo.jpg" width="250px"></a> | <a href="http://nellore.bio/"><img src="https://seekvectorlogo.net/wp-content/uploads/2018/08/oregon-health-science-university-ohsu-vector-logo.png" width="250px"></a> | <a href="https://www.sciserver.org/"><img src="https://skyserver.sdss.org/dr14/en/images/sciserver_logo_inverted_vertical.png" width="250px"></a> |

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=n&d=4xd7F6p1BfdRypx-yEodrXiKhC0xvF0bJJywqR8rMKQ'></script>

<!-- Global site tag (gtag.js) - Google Analytics -->

<script async src="https://www.googletagmanager.com/gtag/js?id=UA-163623894-1"></script>

<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-163623894-1');
</script>
