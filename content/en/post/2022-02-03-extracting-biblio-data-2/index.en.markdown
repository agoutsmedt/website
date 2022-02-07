---
title: "Extracting and Cleaning Bibliometric Data (2)"
author: Aurélien Goutsmedt
date: '2022-02-03'
slug: extracting-biblio-data-2
categories:
  - Bibliometrics
  - Network Analysis
  - R Tutorials
tags:
  - Bibliometrics
  - Network Analysis
  - Quantitative Analysis
  - R
  - Research Tools
subtitle: 'Exploring Dimensions and Constellate'
summary: 'In this post, you will learn how to extract data from Dimensions and Constellate website and how to clean them. These data allow you to build bibliographic networks.'
authors: []
lastmod: '2022-02-03T22:19:06+01:00'
featured: no
draft: yes
lang: en
bibliography: bibliography.bib
#csl:  chicago-author-date.csl
suppress-bibliography: false
link-citations: true
color-links: true # See https://ctan.org/pkg/xcolor for colors
linkcolor: teal
urlcolor: blue
citecolor: red
endnote: false
toc: true
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

{{% toc %}}

The last [post](/post/extracting-biblio-data-1) dealt with extracting bibliometric data from Scopus and presented some steps to clean these data, notably references data. We will do something similar here, but for two other databases: [Dimensions](https://dimensions.ai) and [Constellate](https://constellate.org/), the latter being a beta version of a platform developed by [JSTOR](https://www.jstor.org/). For each database, we will use the data extracted to get some information on our corpus and build networks.

# Dimensions

Dimensions is a relatively newcomer in the world of bibliometric database, in comparison to Scopus or Web of Science. The initial advantage of Dimensions is that the [search application](https://app.dimensions.ai/discover/publication) is open to any one (if I remember well, you just have to create an account).

So let’s begin with the same search than in the last post: publications using Dynamic Stochastic General Equilibrium model.[^1] Like with scopus, we search for “DSGE” *or* “Dynamic Stochastic General Equilibrium”. A difference here is that we can choose between search in “full data” (meaning searching also in the full-text) or in “Title and abstract” (see Figure @ref{fig:dimensions-search}). Doing the first search, we get 27 693 results on February 4, 2022. The fact that we get close to 100 results before the 1990s (when the label DSGE began to be used) means that we could have a lot of false positive. It should be explored more in-depth. But for now and for this tutorial, we will opt for a more secure search, by focusing on titles and abstracts.

<div class="figure">

<img src="dimensions_search.png" alt="Our search on Dimensions app" width="650" />
<p class="caption">
Figure 1: Our search on Dimensions app
</p>

</div>

We obtain 4106 results on February 4, 2022. That is quite much than the 2633 results of our Scopus search in the last [post](/post/extracting-biblio-data-1#using-scopus-website). But I think that it can be partly explain by the fact that Dimensions integrate “preprints” and we have 1532 preprints in our results.

To download the result, click on “Save / Export” on the right of the search bar, and then “Export results”. Two types of export are of interest for us: “Export full record” and “Export for bibliometric mapping”. In the first case, we can export only 500 results against 2500 for the second one (see Figure <a href="#fig:dimensions-export">2</a>). This is not obvious, but the second option allows you to export most metadata, including affiliations and the references cited. What do we lose in comparison to the first export? The publication type (article, preprint, etc…), acknowledgements (that can be useful; see for instance [Paul-Hus et al. 2017](#ref-paul-hus2017)) and categorization of publications. That is not so much. Besides, it means that, by using the second option, you can extract more results that in Scopus (limited to 2000).

<div class="figure">

<img src="dimensions_export.png" alt="Choosing the export format" width="514" />
<p class="caption">
Figure 2: Choosing the export format
</p>

</div>

make a comparison of most cited in the two corpus by importing direct citation

# References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-paul-hus2017" class="csl-entry">

Paul-Hus, Adèle, Philippe Mongeon, Maxime Sainte-Marie, and Vincent Larivière. 2017. “The Sum of It All: Revealing Collaboration Patterns by Combining Authorship and Acknowledgements.” *Journal of Informetrics* 11 (1): 80–87. <https://doi.org/10.1016/j.joi.2016.11.005>.

</div>

</div>

[^1]: Keeping the same search allows us to do some comparisons with Scopus data and observe how it impacts networks and other results.
