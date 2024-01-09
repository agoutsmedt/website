---
title: Mapping Macroeconomics
subtitle: "An interactive platform for the exploration of inter-specialties relationships in macroeconomics 1970 - 2020"
author: 
- Aurélien Goutsmedt
- Pedro Garcia Duarte
- Alexandre Truc
date: '2021-03-02'
slug: mapping-macroeconomics
categories:
  - Bibliometrics
  - History of Macroeconomics
  - Research Project
tags:
  - Bibliometrics
  - History of Macroeconomics
  - Network Analysis
  - R
  - Quantitative Analysis
  - Research Project
summary: "Building an online interactive platform displaying bibliometric data on a large set of macroeconomic articles. Our goal is to settle the basis for a broad and long-run project on the history of macroeconomics, as well as to bring to historians tools to run quantitative inquiries to support their own research work."
authors: []
external_link: https://www.digitalhistoryofscience.org/dhm/
image:
  caption: ''
  focal_point: ''
  preview_only: no
url_code: 'https://github.com/Alex7722/macro_AA'
url_pdf: ''
url_slides: ''
url_video: ''
slides: ''

###
### Bibliography settings
###
bibliography: bibliography.bib
csl: chicago-author-date.csl
link-citations: true

---

> This project has received a grant from the *History of Economics Sociey* [New Initiatives Fund](https://historyofeconomics.org/about-the-society/new-initiatives/). I am collaborating with [Alexandre Truc](https://sites.google.com/view/alexandre-truc/home-and-contact), who is working with me on the data analysis part, and with [Pedro Garcia Duarte](https://www.insper.edu.br/pesquisa-e-conhecimento/docentes-pesquisadores/pedro-garcia-duarte/) who plays the role of advisor on the interpretations and presentations of our results.
>
> You can see the full project demand: [<svg aria-hidden="true" role="img" viewBox="0 0 512 512" style="height:1.1em;width:1.1em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:currentColor;overflow:visible;stroke-width:5px;position:relative;"><path d="M64 464H96v48H64c-35.3 0-64-28.7-64-64V64C0 28.7 28.7 0 64 0H229.5c17 0 33.3 6.7 45.3 18.7l90.5 90.5c12 12 18.7 28.3 18.7 45.3V288H336V160H256c-17.7 0-32-14.3-32-32V48H64c-8.8 0-16 7.2-16 16V448c0 8.8 7.2 16 16 16zM176 352h32c30.9 0 56 25.1 56 56s-25.1 56-56 56H192v32c0 8.8-7.2 16-16 16s-16-7.2-16-16V448 368c0-8.8 7.2-16 16-16zm32 80c13.3 0 24-10.7 24-24s-10.7-24-24-24H192v48h16zm96-80h32c26.5 0 48 21.5 48 48v64c0 26.5-21.5 48-48 48H304c-8.8 0-16-7.2-16-16V368c0-8.8 7.2-16 16-16zm32 128c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H320v96h16zm80-112c0-8.8 7.2-16 16-16h48c8.8 0 16 7.2 16 16s-7.2 16-16 16H448v32h32c8.8 0 16 7.2 16 16s-7.2 16-16 16H448v48c0 8.8-7.2 16-16 16s-16-7.2-16-16V432 368z"/></svg>](./proposal_hes.pdf)
>
> You can find a public repository of the project on github: [<svg aria-hidden="true" role="img" viewBox="0 0 496 512" style="height:1.1em;width:1.07em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:currentColor;overflow:visible;stroke-width:5px;position:relative;"><path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"/></svg>](https://github.com/Alex7722/macro_AA)

{{% toc %}}

## Objective

It takes as a point of departure that economics has been characterized since the 1970s by an exponential increase in the number of articles published in academic journals. This phenomenon makes it harder for historians of economics to properly assess the trends in the transformation of economics, the main topics researched, the most influential authors and ideas, *etc*. As a result, historians of this period run the risk of relying, at least as first pass, on a presentist view of the history of ideas: what today’s economists consider as important contributions from the past and the most influential authors. When historians shield themselves from the retrospective views of the practising economists, they have to delve into the literature of the past that has been forgotten for the most part and to scrutinize the network of authors that are little known. This effort allows historians to correct the potted histories of the practising economists and to propose alternative narratives of the evolution of the discipline.[^1] However, the bigger the literature to be studied is, the harder the historians’ capacity to grasp the overall picture of the time.

We agree with those who consider that developing collective quantitative tools could help historians to confront this challenge. The issues and uses of quantitative tools in history of economics have been the topic of many discussions in our field—see for instance Backhouse ([1998](#ref-backhouse1998)), Claveau and Gingras ([2016](#ref-claveau2016)) and the *Journal of Economic Methodology* special issue in 2018, in particular Edwards, Giraud, and Schinckus ([2018](#ref-edwards2018a)) and Cherrier and Svorenčík ([2018](#ref-cherrier2018a))—, but the technical barrier posed by the methods remains an obstacle for many historians. The challenges and opportunities that a quantitative history brings are particularly useful to the recent history of macroeconomics. Practising macroeconomists are eager to tell narratives of the evolution of their field that serve the purpose of intervening on current debates, by giving credit to particular authors and weight to specific ideas. Historians who go into this area find plenty of accounts by macroeconomists and have to handle the vast increase in the macroeconomic literature since the last quarter of the past century.

Our goal is to build an online interactive platform displaying bibliometric data on a large set of macroeconomic articles. We aim at settling the basis for a broad and long-run project on the history of macroeconomics, as well as to bring to historians tools to run quantitative inquiries to support their own research work.

Our approach is similar to Claveau and Gingras ([2016](#ref-claveau2016)) as we focus on the same bibliometric data and share many common tools.[^2] It differs from and extends it in several ways as our platform will:

- Focus on a smaller part of economics (i.e. macroeconomics) to keep a better control on the results and their interpretation, using the knowledge we have on the history of macroeconomics. In contrast, Claveau and Gingras ([2016](#ref-claveau2016)) offer a broad history of the many specialties in economics since the late 1950s.
- Offer interactions between micro- and macro- levels of analysis, by following the positioning (and the evolution over time of this positioning) of some authors, articles or institutions within the general map brought by network analysis. This would be possible by displaying less aggregated visualisations than Claveau and Gingras ([2016](#ref-claveau2016)).

The goal of our platform is to bring forward general visualizations of the structure of macroeconomics between 1970 and 2020 to:

- Introduce bibliometric and network analysis tools, concepts and results to non-specialists in history of economics;
- Present general results about the structure of macroeconomics:
  - Importance and centrality of particular actors, articles and books, or institutions;
  - Evolution of topics, ideas and subspecialties. For instance, it would allow us to explore the supposed opposition between “fresh water” and “salt water” macroeconomists ([Gordon 1989](#ref-gordon1989)) or the rise of the “New Neoclassical Synthesis” ([Goodfriend and King 1997](#ref-goodfriendking1997)).
- Allow historians (but also macroeconomists) to explore questions of interests for their research:
  - Identify relevant bibliographical documents and actors for a particular object in a simple and efficient way;
  - Check simple claims about particular facts in macroeconomics (e.g., most cited papers by macroeconomists in a given time frame, or the role and importance of particular actors and contributions, searchable on the platform);
  - Find new research directions in relation to under-studied topics or new unexplored patterns found in the data.

## Metholodogy

The first stage of the project is to find a set of articles that properly identifies macroeconomics. In the initial work already done in this project, we have pondered this challenge and one solution is to identify macroeconomic articles from JEL codes. Our procedure led us to develop two different corpora. The first corpus is simply made of all articles identified as macroeconomics by both the old (1969-1990) and new (1991-present) JEL codes system. This corpus is useful to understand how economists classify their own research into categories.

We have also developed a second corpus, less dependent on the economists’ classifications, to identify what composed macroeconomics from a sociological and intellectual perspective. The second corpus uses this first corpus as a point of departure to identify all the articles closely related to macroeconomics with a two steps procedure that we apply to the old and new JEL codes corpus: (1) identify the core of macroeconomics by isolating the most cited references; (2) extending the core by identifying the articles citing several articles of the core or cited by several articles of the core.

Our analysis of this corpus will heavily rely on network analysis, and particularly on bibliographic coupling networks, which links articles depending on the number of references they share in their bibliography. We will then use the Leiden algorithm ([Traag, Waltman, and van Eck 2019](#ref-traag2019)) to identify communities in this type of networks, for different period. An important step will be to characterize qualitatively this community to understand what they represent. It would also allow us to explore the role of different academic journals and institutions in macroeconomics (which are the main journals over time, how institutions specialised in sub-specialties of macroeconomics and how they structured the field, *etc*.).

The online platform we want to create would allow the user to explore our data and visualizations. First, the user would be able to navigate in our networks, by zooming and clicking on the nodes to identify them, but also to identify in the network the articles, authors or institutions she is interested in thanks to a search engine. Second, the user would be able to select the period she is interested in, and to generate the corresponding networks, but also citation statistics depending on the dates chosen.

## Tools

The repository of the project with our R scripts is on github [<svg aria-hidden="true" role="img" viewBox="0 0 496 512" style="height:1.5em;width:1.45em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:currentColor;overflow:visible;stroke-width:5px;position:relative;"><path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"/></svg>](https://github.com/Alex7722/macro_AA).

The data analysis (extracting the corpus, building networks and analysing them) part is done with R. With Alexandre Truc, we are currently developping two R packages to support this project: [biblionetwork](https://agoutsmedt.github.io/biblionetwork/) and [networkflow](https://github.com/agoutsmedt/networkflow). The second one heavily relies on igraph ([Csardi and Nepusz 2006](#ref-gabor2006)), tidygraph ([Pedersen 2020b](#ref-pedersen2020a)) and ggraph ([Pedersen 2020a](#ref-pedersen2020b)) great packages.

The interactive platform will be built by resorting to the [Sigma javascript library](http://sigmajs.org/), which is also used for the software [GEPHI](https://gephi.org/).

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-backhouse1998" class="csl-entry">

Backhouse, Roger E. 1998. “The Transformation of U.S. Economics, 1920-1960, Viewed Through a Survey of Journal Articles.” *History of Political Economy* 30 (4): 85–107. <http://search.ebscohost.com/login.aspx?direct=true&db=bth&AN=7752166&lang=fr&site=ehost-live>.

</div>

<div id="ref-cherrier2018a" class="csl-entry">

Cherrier, Beatrice, and Andrej Svorenčík. 2018. “The Quantitative Turn in the History of Economics: Promises, Perils and Challenges.” *Journal of Economic Methodology* 0 (0): 1–11. <https://doi.org/10.1080/1350178X.2018.1529217>.

</div>

<div id="ref-claveau2016" class="csl-entry">

Claveau, François, and Yves Gingras. 2016. “Macrodynamics of Economics: A Bibliometric History.” *History of Political Economy* 48 (4): 551–92. <https://read.dukeupress.edu/hope/article-abstract/48/4/551/12684/Macrodynamics-of-Economics-A-Bibliometric-History>.

</div>

<div id="ref-gabor2006" class="csl-entry">

Csardi, Gabor, and Tamas Nepusz. 2006. “The Igraph Software Package for Complex Network Research.” *InterJournal* Complex Systems: 1695. <https://igraph.org>.

</div>

<div id="ref-duppe2014a" class="csl-entry">

Düppe, Till, and E. Roy Weintraub. 2014. *Finding Equilibrium: Arrow, Debreu, McKenzie and the Problem of Scientific Credit*. Princeton: Princeton University Press.

</div>

<div id="ref-edwards2018a" class="csl-entry">

Edwards, José, Yann Giraud, and Christophe Schinckus. 2018. “A Quantitative Turn in the Historiography of Economics?” *Journal of Economic Methodology* 25 (4): 283–90. <https://doi.org/10.1080/1350178X.2018.1529133>.

</div>

<div id="ref-forder2014" class="csl-entry">

Forder, James. 2014. *Macroeconomics and the Phillips Curve Myth*. Oxford: Oxford University Press.

</div>

<div id="ref-goodfriendking1997" class="csl-entry">

Goodfriend, Marvin, and Robert King. 1997. “The New Neoclassical Synthesis and the Role of Monetary Policy.” In *Macroeconomics Annual 1997*, edited by NBER, 231–96. Cambridge (MA): MIT Press.

</div>

<div id="ref-gordon1989" class="csl-entry">

Gordon, Robert J. 1989. “Fresh Water, Salt Water, and Other Macroeconomic Elixirs.” *Economic Record* 65 (2): 177–84.

</div>

<div id="ref-medema2014" class="csl-entry">

Medema, Steven G. 2014. “The Curious Treatment of the Coase Theorem in the Environmental Economics Literature, 1960–1979.” *Review of Environmental Economics and Policy* 8 (1): 39–57.

</div>

<div id="ref-pedersen2020b" class="csl-entry">

Pedersen, Thomas Lin. 2020a. *Ggraph: An Implementation of Grammar of Graphics for Graphs and Networks*. <https://CRAN.R-project.org/package=ggraph>.

</div>

<div id="ref-pedersen2020a" class="csl-entry">

———. 2020b. *Tidygraph: A Tidy API for Graph Manipulation*. <https://CRAN.R-project.org/package=tidygraph>.

</div>

<div id="ref-traag2019" class="csl-entry">

Traag, Vincent A, Ludo Waltman, and Nees Jan van Eck. 2019. “From Louvain to Leiden: Guaranteeing Well-Connected Communities.” *Scientific Reports* 9 (1): 1–12.

</div>

</div>

[^1]: See for instance Forder’s -Forder ([2014](#ref-forder2014)) deconstruction of the Phillips curve “myth”, Düppe and Weintraub’s -Düppe and Weintraub ([2014](#ref-duppe2014a)) analysis of scientific credit about the general equilibrium proof, or Medema ([2014](#ref-medema2014)) on the different meanings of the Coase theorem.

[^2]: See Claveau and Gingras’s platform [here](http://www.digitalhistoryofscience.org/economics/).
