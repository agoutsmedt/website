---
title: Release of biblionetwork 0.1.0
author: Aurélien Goutsmedt
date: '2021-04-09'
slug: release-biblionetwork
bibliography: REFERENCES.bib
categories:
  - Bibliometrics
  - R Package
tags:
  - Bibliometrics
  - R
  - R Package
subtitle: ''
summary: ''
authors: []
lastmod: '2021-04-09T15:29:25+02:00'
featured: no
draft: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

I am very pleased to announce the initial release of [biblionetwork](https://agoutsmedt.github.io/biblionetwork/) to CRAN! biblionetwork is designed to build easily and quickly large list of edges for bibliometric networks. You can identify the edges for different types of network (bibliometric coupling or co-citation, or co-authorship networks) and use different methods to calculate the weights of edges.

Install biblionetwork with:

``` r
install.packages("biblionetwork")
```

## Usage

The basic function of the package is the `biblio_coupling()` function. This function calculates the number of references that different articles share together, as well as the coupling angle value of edges in a bibliographic coupling network (Sen and Gan 1983). What you need is just a file with entities (documents, authors, universities, *etc.*) citing references.[^1]

This example use the [data incorporated](https://agoutsmedt.github.io/biblionetwork/reference/index.html) in the package.[^2]

``` r
library(biblionetwork)
biblio_coupling(Ref_stagflation, 
                source = "Citing_ItemID_Ref", 
                ref = "ItemID_Ref", 
                normalized_weight_only = FALSE, 
                weight_threshold = 1)
```

    ##             from         to     weight nb_shared_references     Source
    ##    1:     214927    2207578 0.14605935                    4     214927
    ##    2:     214927    5982867 0.04082483                    1     214927
    ##    3:     214927    8456979 0.09733285                    3     214927
    ##    4:     214927   10729971 0.29848100                    7     214927
    ##    5:     214927   16008556 0.04714045                    1     214927
    ##   ---                                                                 
    ## 2712: 1111111161 1111111172 0.03434014                    1 1111111161
    ## 2713: 1111111161 1111111180 0.02003610                    1 1111111161
    ## 2714: 1111111161 1111111183 0.04050542                    2 1111111161
    ## 2715: 1111111172 1111111180 0.03646625                    1 1111111172
    ## 2716: 1111111182 1111111183 0.27060404                    8 1111111182
    ##           Target
    ##    1:    2207578
    ##    2:    5982867
    ##    3:    8456979
    ##    4:   10729971
    ##    5:   16008556
    ##   ---           
    ## 2712: 1111111172
    ## 2713: 1111111180
    ## 2714: 1111111183
    ## 2715: 1111111180
    ## 2716: 1111111183

## What you can do with biblionetwork

The package incorporates different types of method for calculating edges weight, depending on the type of network your working on and the variables you want to take into account. You will find on the package website a detailed [vignette](https://agoutsmedt.github.io/biblionetwork/articles/Using_biblionetwork.html) on these different methods and how to use the package for different networks.

## Acknowledgements

The original function to find edges and calculate weights for large networks was developed by François Claveau. The different functions in this package have been developed, from Claveau’s original idea, by Alexandre Truc and Aurélien Goutsmedt. The package is maintained by Aurélien Goutsmedt.

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-goutsmedt2021a" class="csl-entry">

Goutsmedt, Aurélien. 2021. “From the Stagflation to the Great Inflation: Explaining the US Economy of the 1970s.” *Revue d’Economie Politique* Forthcoming. <https://aurelien-goutsmedt.com/media/pdf/stagflation-great-inflation.pdf>.

</div>

<div id="ref-sen1983" class="csl-entry">

Sen, Subir K., and Shymal K. Gan. 1983. “A Mathematical Extension of the Idea of Bibliographic Coupling and Its Applications.” *Annals of Library Science and Documentation* 30 (2). <http://nopr.niscair.res.in/bitstream/123456789/28008/1/ALIS%2030(2)%2078-82.pdf>.

</div>

</div>

[^1]: If you want to build a coupling network with entities larger than a document (meaning entities that have published several documents, and thus can cite a reference several times), we rather recommend the use of the [coupling\_entity()](https://agoutsmedt.github.io/biblionetwork/reference/coupling_entity.html) function.

[^2]: The biblionetwork package contains bibliometric data built by Goutsmedt (2021). These data gather the academic articles and books, published between 1975 and 2013, that endeavoured to explain the United States stagflation of the 1970s. They also gather all the references cited by these articles and books on stagflation. The `Nodes_stagflation.rda` file contains information about the academic articles and books on stagflation (the staflation documents), as well as about the references cited at least by two of these stagflation documents. The `Ref_stagflation.rda` is a data frame of direct citations, with the identifiers of citing documents, and the identifiers of cited documents. The `Authors_stagflation.rda` is a data frame with the list of documents explaining the US stagflation, and all the authors of these documents (`Nodes_stagflation.rda` just takes the first author for each document).
