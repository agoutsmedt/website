---
output: hugodown::hugo_document

slug: {{ slug }}
title: {{ title }}
date: {{ date }}
author: {{ author }}
summary: >
    A 2-3 sentence description of the post that appears on the articles page.
    This can be omitted if it would just recapitulate the title.

tags: []
categories: []
date: {{ .Date }}
lastmod: {{ .Date }}
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

###
### Bibliography settings
###
bibliography: assets/bibliography/bibliography.bib
csl:  assets/bibliography/chicago-author-date.csl
suppress-bibliography: false
link-citations: true
color-links: true # See https://ctan.org/pkg/xcolor for colors
linkcolor: teal
urlcolor: blue
citecolor: red
endnote: false

###
### Formatting settings
###
toc-title: "Table des matières"
toc: true # Table of contents
toc_depth: 2
---
