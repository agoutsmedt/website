---
title: "Introduction à la recherche en histoire et philosophie de l'économie"
author: Aurélien Goutsmedt
date: '2021-03-01'
slug: introduction-mehpere
categories: [MEHPERE]
tags:
  - Research Methods
  - Historiography
  - Research Tools
subtitle: ''
summary: "Introduction à la recherche en histoire et philosophie de l'économie et à différents outils et pratiques utiles pour l'écriture d'un mémoire de recherche"
type: book
authors: []
lastmod: '2021-03-01T14:38:29+01:00'
featured: no
draft: no
bibliography: bibliography_intro.bib
suppress-bibliography: false
link-citations: true
color-links: true ## See https://ctan.org/pkg/xcolor for colors
linkcolor: teal
urlcolor: blue
citecolor: red
endnote: false
toc-title: "Table des matières"
toc: true ## Table of contents
toc_depth: 2
lof: false ## List of figures
lot: false ## List of tables
fontsize: 12pt
linestretch: 1.5
## Uncomment and check https://tug.org/FontCatalogue/ and https://fonts.google.com/ for fonts
## mainfont: "Merriweather"
## sansfont: "Raleway"
## monofont: "IBM Plex Mono"
## mathfont:
documentclass: article ## See https://en.wikibooks.org/wiki/LaTeX/Document_Structure#Document_classes for more classes and options
classoption: [notitlepage, onecolumn, openany]
geometry: [a4paper, bindingoffset=0mm, inner=30mm, outer=30mm, top=30mm, bottom=30mm] ## See https://ctan.org/pkg/geometry for more options
header-includes:
   - \usepackage{hyperref}
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
weight: 10
editor_options: 
  markdown: 
    wrap: 72
---

{{% callout note %}} Des slides sont également disponibles: [première
séance](../Cours_MEhPERE_séance1.pdf) et [deuxième
séance](../Cours_MEhPERE_Ecriture.pdf). {{% /callout %}}

## Cerner le sujet et trouver une question de recherche {#cerner-sujet}

### Affiner son sujet {#affiner-son-sujet}

La première étape consiste à réussir à passer d’un thème vague à
quelques chose de plus précis. Lorsqu’on construit un sujet, on se
heurte à différents problèmes récurrents :

-   Les **termes sont trop vastes** (“économie”, “mathématisation”,
    “modèles”, “valeur”, “inégalités”). Il s’agit alors par exemple de
    se poser la question de quel sous-champ de l’économie on veut/penser
    parler ? Sur le sujet de la mathématisation, on peut par exemple
    décider de se concentrer sur la théorie de l’équilibre général (ce
    qui n’empêche pas d’essayer de dire des choses générales sur
    l’économie). Ou encore, de quel type de mathématisation parle-t-on
    (exemple: montée de l’axiomatisation et de la théorie ensembliste) ?
-   Quelle **temporalité** ? Pourquoi ? Penser également à la question
    **géographique**, à l’opposition national/régional, local/mondial.
    Réfléchir à l’intérêt de situer géographiquement son sujet.
-   Quelles questions mon sujet posent ? En quoi cela est intéressant ?
    Quelles **problématiques** intéressantes pourrais-je construire à
    partir de là? Important de poser à l’écrit une première salve de
    questions, sur lesquelles vous tenterez d’élaborer ensuite, ne
    serait-ce que pour tester à quel point vous pouvez pousser votre
    sujet et en tirer des réflexions intéressantes.
-   Il est important de se mettre au clair sur vos **préconceptions
    sous-jacentes** : par exemple, pourquoi est-ce que je travaille sur
    la mathématisation de l’économie ? Est-ce parce que je considère
    qu’il y a un rôle trop important des maths en économie ? Il est
    important de neutraliser ou de canaliser ses préconceptions.

Neutraliser et canaliser ses préconceptions signifient, entre autres,
qu’il faut s’évertuer à être “charitable” avec l’auteur que l’on étudie
: plutôt que de penser que l’efficience des marchés ou les anticipations
rationnelles sont des hypothèses stupides, totalement irréalistes, il
faut essayer de comprendre pourquoi ces hypothèses ont été adoptées si
généralement ? Pourquoi des gens intelligents utilisent ces outils ?
Quelle préconception, quelle épistémologie, quelle méthodologie, quels
objectifs (rhétoriques, institutionnels, scientifiques), quelles
pratiques sociales derrière ?

{{% callout note %}} Ne pas se faire écraser trop tôt par la question de
la structure de votre mémoire. Cela viendra après. {{% /callout %}}

Une autre façon de “travailler” son sujet, c’est de lui poser un
certains nombres de questions assez simples :

-   **Qui?** : qui sont ces gens à qui je m’intéresse ? Que font-ils ?
    Quels sont leurs réseaux ? Penseurs, économistes, philosophes,
    groupe de recherche, département, profession, champs, sous-champs…
-   **Quoi?** : Qu’est-ce que l’on souhaite observer ? Et pourquoi ? Des
    pratiques, concepts, un savoir, un instrument, la trajectoire d’un
    individu, d’un groupe, …
-   **Quand et où?** : Contexte spatio-temporel / Evènement / bornes /
    ruptures et révolutions / continuité / sentiers de dépendance /
    traditions nationales / Internationalisation et américanisation.
-   **Comment ?** : En analysant des sources et en choisissant des
    matériaux à utiliser.

### Typologie de sujets {#typologie-sujet}

Il faut faire attention à l’histoire d’un auteur unique. Si elle a
l’avantage de permettre de cerner facilement un corpus (sauf si on a
déjà beaucoup écrit sur cette auteur, *#AdamSmith*). Difficulté si
beaucoup a été dit dessus, difficulté s’il n’y a pas trop de littérature
secondaire sur cet auteur. Comment réussir à souligner l’intérêt d’un
auteur par rapport à d’autres, si on focalise son travail uniquement sur
cet auteur? Cela peut conduire également à certaines difficultés
également pour dégager des résultats généralisables.

Des fois, il est plus productifs et plus intéressant de :

-   Se centrer sur une méthode : les randomisations aléatoires \[par
    exemple, la thèse de @favereau2014; et son résumé
    @favereau2014b\], la comptabilité à partie double \[un classique de
    la sociologie de la quantification: @carruthers1991\], les
    expériences de laboratoires, *etc.*

-   Etudier un objet institutionnel : le revenu universel, une revue
    scientifique particulière \[sur *History of Political Economy* voir
    @giraud2019\], les JEL codes \[@cherrier2017\], des modèles
    macroéconomiques dans des institutions \[@cherrier2019\], la
    discrimination \[la thèse de @chassonnery-zaïgouche2014\], *etc*.

-   Etudier un concept/objet économique : la stagflation
    \[@goutsmedt2021\], la discrimination \[la thèse de
    @chassonnery-zaïgouche2014\], les biens publics \[la thèse de
    @desmarais-tremblay2016\], la performativité des théories
    économiques \[la thèse de @brisset2014\], la souveraineté du
    consommateur, *etc*.

-   Penser en termes de géographie/faire varier les zones géographiques :  
    l’économie en Inde \[voir le résumé de la thèse de @bach2020\],
    la lecture des auteurs classiques par les économistes chinois
    \[@xiao2021\].[^1]

-   Mettre des auteurs en relation les uns avec les autres.

-   S’intéresser aux controverses scientifiques (attention, si quelque
    chose est déjà connu comme une “controverse scientifique”, c’est
    sans doute trop connu pour faire son mémoire dessus. Ex: controverse
    Vining-Koopmans/ Keynes-Tinbergen).[^2]

-   S’intéresser à des groupes d’économistes: histoire du MIT
    \[@cherrier2014\], communauté des nouveaux classiques, économistes
    de la régulation/convention, des conférences (permet de voir les
    discussions entre auteurs)[^3], les prix et récompenses (Prix
    Nobels, John Bates Clark medal, Prix du meilleur jeune économiste,
    *etc*.).

*Typologie des questions de recherche*. On peut souvent “trouver” sa
question de recherche à partir des ces grandes “questions-type” :

-   Origine, filiation, “influence” : “d’où vient” une idée, une
    pratique, une théorie, un modèle, un objet de recherche, une forme
    de quantification, un standard professionnel, etc.[^4]

-   Réception : “où va” une idée, une pratique, une théorie, un objet,
    etc. (l’inverse de la question précédente : “amont - aval”).

    -   Sous-questions : par quels canaux (individus, formations,
        revues, institutions, médias) se fait la diffusion ? Quelles
        résistances elle rencontre (controverses, débats, oppositions,
        compétitions, …)

-   Comparaison : “en quoi X est différent de Y” ? (sujet plus
    “statique” vs. “dynamique” de l’origine ou réception). Délimiter X
    ou Y (champ, approche, théorie, modèle, auteur, etc.).

    -   Sous-questions : “dimension” de la comparaison (analytique,
        empirique, pratique, politique, méthodologique, épistémologique)
        ; “rupture ou continuité ?”

Attention aux questions bateaux :

-   “que pense X de tel ou tel sujet?”. Vous courrez le risque de faire
    une analyse sans relief (qui se contenterait de répéter ce que
    n’importe qui pourrait dire s’il lisait les mêmes textes), sauf si
    on dispose de matériaux inédits (archives, entretiens) et qu’on a
    une façon de motiver pourquoi c’est intéressant (par exemple : ce
    que pense X de tel sujet influence ce que pense X de tel autre sujet
    connu ; mais du coup on retombe bien sur une question de recherche
    du type “influence”/origine).
-   “X est incohérent sur tel sujet” => risque de faire une critique
    peu charitable, parti pris.
-   “X c’est vraiment génial, original et inédit” => risque de produire
    une apologie, un parti pris.

{{% callout note %}} Un sujet se construit en permanence. Jusqu’à
l’écriture, vous serez en train de le retravailler, de l’affiner.
Notamment car vous allez lire plein de choses durant votre travail de
recherche. Ce processus est normal. {{% /callout %}}

### Aller plus loin sur les types de sujet : quelques références en historiographie

L’histoire de la pensée économique n’a pas été épargnée par les débats
sur les bonnes d’écrire l’histoire. Ces débats ont le mérite de poser
sur la table de nombreuses questions historiographiques et d’interroger
le chercheur (et donc l’étudiant qui doit écrire un mémoire de
recherche) sur la manière d’interroger sont sujets, sur les méthodes
mobilisées, ainsi que sur la perspective historiographique adoptée.
L’étudiant pourra ainsi trouvée quelques réponses, mais surtout voir
émerger de nouvelles questions, à la lecture, pour l’histoire de l’économie et
de la pensée économique, de Backhouse ([1992](#ref-backhouse1992a)), Backhouse ([2001](#ref-backhouse2001a)), Emmett ([2014](#ref-emmett2014)),
Fontaine ([2016](#ref-fontaine2016)), Forget ([2005](#ref-forget2005)), Hands ([1997](#ref-hands1997)), Lapidus ([2019](#ref-lapidus2019)), Weintraub ([1999](#ref-weintraub1999a)), Weintraub ([2005](#ref-weintraub2005)),
Winch ([2018](#ref-winch2018)), Stapleford ([2017](#ref-stapleford2017a)). Pour d’autres débats en histoire de la philosophie et en
histoire des sciences, voir: Collini ([1988](#ref-collini1988a)), Passmore ([1965](#ref-passmore1965)), Rorty ([1984](#ref-rorty1984a)), Seidman ([1983](#ref-seidman1983a)),
Thomas ([2017](#ref-thomas2017)), Wilson ([2017](#ref-wilson2017)).

## Délimiter et construire un corpus

### Où chercher ?

Une première série d’outils, les bases de données bibliographiques:

-   [Domino](http://maki.univ-paris1.fr/V/I3HLXLN4NBI91PCBGMN4XF754YKGJEH5L9I7KNQUJTPQUJ86P7-08407?RN=191328684&pds_handle=GUEST) : c’est l’outil de Paris 1 qui permet d’avoir accès aux
    différentes ressources documentaires de Paris 1, dont les
    différentes bases de données bibliographiques (comme
    [JSTOR](https://www.jstor.org/) ou
    [econlit](https://www.aeaweb.org/econlit/)). Permet aussi de
    chercher plus précisément où trouver une revue électronique.
    Domino vous donne par exemple également accès au [New Palgrave
    Dictionary of
    Economics](https://link.springer.com/referencework/10.1057/978-1-349-95121-5),
    ressource utile pour avoir une bonne base sur certains concepts
    économiques et repérer les références majeures. Depuis 2020,
    Domino est en cours de remplacement par *Mikado*.

-   Le [Sudoc](http://www.sudoc.abes.fr/cbs/?COOKIE=U10178,Klecteurweb,D2.1,E7b95abca-0,I250,B341720009+,SY,QDEF,A%5C9008+1,,J,H2-26,,29,,34,,39,,44,,49-50,,53-78,,80-87,NLECTEUR+PSI,R178.51.156.3,FN) : c’est la base de données regroupant les différents catalogues
    des bibliothèques universitaires. Très utile pour chercher une
    thèse par exemple. L’avantage de faire de la recherche à Paris,
    et qu’on peut retrouver un certain nombre de document (en
    utilisant le sudoc) dans certaines bibliothèques universitaires
    parisiennes.

-   [Google scholar](https://scholar.google.com/) : c’est le moteur de
    recherche le plus efficace pour trouver des références. Quand vous
    êtes sur le réseau Paris 1, il est plus simple de chercher
    directement sur google scholar qui vous proposera automatiquement le
    PDF que de passer par Domino.

-   Un nouvel outil de recherche bibliographique (et d’analyse
    bibliométrique) à tester: [Dimensions](https://www.dimensions.ai/).
    Permet d’avoir accès notamment à des rapports d’institutions.

Au-delà de ces bases de données bibliographiques, il y a d’autres moyens
de trouver des références sur votre sujet:

-   pensez à regarder les bibliographies des manuels et *handbooks* ;

-   souvent la recherche bibliographique est un processus itératif :
    vous trouvez de nouvelles références dans les bibliographiques des
    nouveaux textes que vous lisez ;

-   les *books reviews* publiés par les revues académiques ;

-   pensez à demander aux autres étudiants et aux chercheurs qui
    travaillent plus ou moins sur les mêmes sujets que vous ;

-   Twitter peut parfois être un outil de veille intéressant.

Il est également important de savoir quelles sont les revues qui
publient en histoire de la pensée économique et en
philosophie/épistémologie économique. C’est souvent également une bonne
manière d’avoir une idée de ce qu’il se fait dans le champ. Voici une
liste quasi-exhaustive:

-   [History of Political Economy](https://read.dukeupress.edu/hope) ;
-   [European Journal of History of Economic
    Thought](https://www.tandfonline.com/toc/rejh20/current) ;
-   [Journal of the History of Economic
    Thought](https://www.cambridge.org/core/journals/journal-of-the-history-of-economic-thought)
    ;
-   [History of Economic Ideas](http://www.historyofeconomicideas.com/)
    ;
-   [OEconomia](https://journals.openedition.org/oeconomia/) ;
-   [Cahiers d’économie
    politique](https://www.cairn.info/revue-cahiers-d-economie-politique.htm)
    ;
-   [Journal of Economic
    Methodology](https://www.tandfonline.com/toc/rjec20/current) ;
-   [Philosophy &
    Economics](https://www.cambridge.org/core/journals/economics-and-philosophy)
    ;
-   [Politics, Philosophy &
    Economics](https://journals.sagepub.com/home/ppe).

### Savoir lire en diagonale

Face à une littérature primaire et secondaire qui s’allonge souvent très
vite, il faut trouver des moyens de traiter toute cette information de
manière efficace. Les notes de lectures (*book reviews*) sont une bonne
manière de se faire une idée rapide du contenu d’un livre. Pour les
articles, comme pour les livres, le plus simple est de lire rapidement
l’introduction (voire la conclusion). Vous pourrez toujours vous pencher
plus avant sur le contenu de l’article si vous pensez pouvoir y trouver
des éléments factuels intéressants, ou bien s’il s’agit d’un article qui
sera central dans votre mémoire.

Il est important de prendre des notes sur ce que vous lisez (cela rentre
dans la pratique du “carnet de bord” ou “*research log*”; voir
[ci-dessous](#fiches)).

### Sources et méthodes de la recherche

Différents matériaux appellent différents traitements/méthodes. Et ces
différents matériaux et méthodes sont complémentaires et peuvent vous
permettre de dégager des résultats intéressants dans vos mémoires.

#### Sources textuelles : littérature primaire/secondaire

On distingue en général littérature primaire (ce que vous étudiez) et
littérature secondaire (ce qui parle de ce que vous étudiez). Au-delà
des classiques articles académiques et livres, il y a des sources
textuelles primaires plus originales:

-   les retranscriptions de séminaires et de conférences ;

-   la “littérature grise” (rapports d’institutions, documents de la
    politique économique, auditions) ;

-   les retranscriptions d’interviews et l’histoire orale ;

-   les articles presse ou de blogs/forums (ou dans les médias en
    général, radio, télé) ;

-   les écrits dans les réseaux sociaux.

#### Archives {#archives}

Quelques exemples d’archives intéressantes accessibles à Paris ou depuis
votre fauteuil :

-   [archives de Bercy](https://www.economie.gouv.fr/saef) ;
-   [archives de
    l’EHESS](https://www.fmsh.fr/fr/diffusion-des-savoirs/archives-fondation)
    ;
-   [archives de la banque de
    France](https://www.banque-france.fr/la-banque-de-france/histoire/archives-historiques)
    ;
-   [archives de la
    Fed](https://www.federalreserve.gov/monetarypolicy/fomchistorical1973.htm)
    ;
-   [archives de Margaret
    Thatcher](https://www.margaretthatcher.org/archive/search.asp) ;
-   [archives de l’Union
    Européenne](https://www.eui.eu/en/academic-units/historical-archives-of-the-european-union).

{{% callout note %}} Cela vaut toujours le coup de se demander s’il
existe des archives en ligne, ou facilement accessible, et de réfléchir
à ce qui pourrait nous être utile. {{% /callout %}}

Pourquoi recourir aux archives?

-   Quand on travaille sur des périodes plus récentes, cela permet
    d’avoir accès à des écrits différents des standards de la recherche
    et de la structure classique d’un article académique (via des
    brouillons, des rapports de recherche, de la correspondance…) ;
-   La correspondance permet justement d’avoir accès aux échanges entre
    économistes et constitue un matériel intéressant pour l’étude des
    controverses ;
-   C’est par les archives qu’on peut essayer de comprendre
    l’implication des économistes dans le débat public et leur rapport à
    l’expertise ;
-   Les archives sont un matériaux essentiels pour retracer l’histoire
    d’institutions (banques centrales, revues, universités…).

Cela peut également être un plus dans vos recherches car les archives
vous donnent accès à des matériaux moins connus que des publications
officielles (voir inédits) et contribuent donc à l’originalité de votre
travail.

Une fois que vous avez trouvé un fonds d’archives qui vous intéresse, il
est important de voir si vous pouvez accéder à ce fonds et les
conditions générales. Renseignez vous sur le matériel que vous pouvez
emmener en salle de consultation (votre ordinateur?) et s’ils vous sera
possible de prendre des photos ou de faire des photocopies. Aujourd’hui,
avec la qualité des appareils photos dans les téléphones, il est assez
simple de prendre soi-même en photos ses archives (au-delà de 10
megapixels la qualité est ok). Vous pouvez recourir à des applications
de “scanner” (tel
[AdobeScan](https://www.adobe.com/be_fr/acrobat/mobile/scanner-app.html))
qui permettent de prendre des photos, d’organiser vos photos en pdf, et
de la reconnaissance de texte
(l’[OCR](https://fr.wikipedia.org/wiki/Reconnaissance_optique_de_caract%C3%A8res))
en temps réel.

Il est également important de préparer d’avance votre grille de
classement et d’analyse de vos archives. Voici un exemple d’une telle
grille :

| Box | Folder                         | Type   | Date    | Keyword    | Summary                                                                   | Scan |
|-----|--------------------------------|--------|---------|------------|---------------------------------------------------------------------------|------|
| 38  | Schultze’s files paper         | Memo   | 22-7-78 | Amendment  | current situation in Congress. Explaining the political divisions         | Yes  |
| 122 | Schultze’s Briefing book files | Letter | 21-5-79 | Keyserling | Keyserling’s disappointment regarding current policy against unemployment | No   |

#### Interview:

Suivant les types de sujets choisis (en général pour les objets d’études
plus récents), il est intéressant de réaliser des interviews.

-   Permet de confirmer quelques pistes de réflexion/obtenir des infos
    inaccessibles ;
-   Permet également d’avancer plus vite sur sa recherche, d’obtenir des
    infos qu’on aurait pu trouver soit même, mais plus rapidement grâce
    à la connaissance et l’expertise de la personne qu’on interview ;
-   Confronter les points de vue par la triangulation des interviews
    pour comprendre les positionnements des différents acteurs (utile
    par exemple dans l’étude des controverses) ;
-   Apprentissage d’une compétence supplémentaire valorisable.

Pour la méthode de l’interview voir @dechadarevian1997, @jullien2019
et le classique de Howard @becker2020 .

Quelques conseils de base pour une interview réussie :

-   Il est important de bien préparer son interview en étudiant en
    détail le CV de l’interviewé, et prenant des notes factuelles pour
    montrer à l’interviewé que l’on connaît le sujet et que l’on a
    travaillé en amont. Savoir montrer qu’on maîtrise le sujet tout en
    posant des questions relativement large ;

-   Pensez à structurer votre interview avec trois ou quatre grand
    thèmes. Vous pouvez ensuite construire une grille d’interview en
    trois colonnes: les grandes questions suivant la structure de votre
    interview, des relances pour chacune de ces grandes questions, ce
    que l’on sait déjà à propos des questions que l’on pose) ;

-   Le “comment?” plutôt que le “pourquoi?”. Vous pouvez transformer
    toutes vos questions de manière à ce qu’elles soient formulées en
    termes de “comment?” plutôt que de “pourquoi?”. La seconde forme
    peut plus facilement braquer votre interlocuteur. La première
    formulation appelle des détails factuels et paraît plus inoffensive
    ;

-   Laissez votre interlocuteur parler ;

-   Posez des questions larges où l’interlocuteur donne son avis/à
    mélanger avec des questions techniques/précises, sur des points
    d’infos dont vous avez besoin.

#### Méthodes quantitatives

Les méthodes quantitatives commencent à se développer assez largement en
histoire de la pensée économique et en philosophie/méthodologie
économique. Pour plus d’information sur ce type de méthodes, vous pouvez
aller jeter un coup d’oeil à ce
[cours](https://aurelien-goutsmedt.com/fr/courses/mehpere/02-2021-quantitative_analysis/)
du séminaire
[MEHPERE](https://aurelien-goutsmedt.com/fr/courses/mehpere/).

Quelques outils assez simple peuvent vous permettre de dégager quelques
réflexions quantitatives sur votre sujet:

-   [Google Books Ngram viewer](https://books.google.com/ngrams)
    (exemple Walras, Menger, Jevons / English, French, German) ;

-   Google scholar et bibliométrie basique
    ([exemple](https://scholar.google.fr/citations?user=nRWVCBQAAAAJ&hl=fr&oi=ao)
    avec Becker). Permet de voir l’évolution des citations de Becker,
    ses papiers les plus cités, comparer avec d’autres économistes,
    d’autres articles…

-   La plateforme [Constellate](https://constellate.org/) développée par
    JSTOR, qui est encore en version Beta mais qui permet de faire des
    analyses intéressantes
    ([exemple](https://constellate.org/builder/?keyword=%22Invisible%20Hand%22&start=1900&end=2021)
    avec la “main invisible”). L’application repère des mots dans le
    plein texte des documents recensés sur JSTOR (pas très complet pour
    le moment), et vous propose un tableau de bord pour analyser les
    publications qui utilisent les mots auxquels vous vous intéressez.

Il faut avoir conscience du fait que ces outils sont encore assez
primaires. Ils peuvent être une première étape pour tester quelques
intuitions, faire émerger quelques surprises, qu’il faudra ensuite
creuser de manière plus approfondie (qualitativement ou
quantitativement).

Parmi les méthodes quantitatives utilisées en HPE et en philosophie
économique, on trouve:

-   Analyse textuelle (analyse de fréquence et TF-IDF, analyse de
    sentiment, topic-modelling, *etc*.) ;

-   Bibliométrie ;

-   Analyse de réseau (réseaux de citations, réseaux de vocabulaire,
    réseaux sociologiques) ;

-   Prosopographie (biographie collective), à mi-chemin entre analyse
    quantitative et qualitative ;

-   Statistiques et économetrie (ACM, ACP, régressions…).

## Organiser le travail et traiter l’information

Plusieurs outils et pratiques peuvent vous permettre d’organiser votre
travail de recherche et de traiter l’information requise plus
efficacement. Nous nous concentrons ici sur trois pratiques/outils.

### Les tableaux pour classer l’information

Plutôt que des longues listes d’information dans un document texte, il
est souvent utile de recourir à des tableaux pour classer certaines
informations:

-   archives récoltées ([voir ci-dessus](#archives)) ;

-   liste des individus auxquels vous vous intéressez ;

-   Liste de modèles, ou liste d’articles sur un même sujet ;

-   Chronologie.

Le but est de construire une grille d’analyse systématique, et le
tableau vous permet d’embrasser d’un coup d’œil l’information récoltée,
de catégoriser vos éléments, de renvoyer vers d’autres informations.

### Fiches de lecture et *Research Log* {#fiches}

Pour chaque article/livre que vous lisez, prenez quelques notes sur
l’argument général de l’article et la thèse (plus ou moins explicite) de
l’article. S’il y a des matériaux intéressant (informations, citations,
arguments) qui pourront vous être utiles plus tard, pensez à les noter
et à référencer la page. Prenez également des notes sur ce que vous
pensez de l’article (est-ce convaincant? quels sont les points forts et
points faibles) et à souligner en quoi ça peut vous aider pour votre
mémoire. Cela prend un peu de temps au début et nécessite de s’impliquer
plus activement dans la lecture (ce qui est une bonne chose), mais il
est important de garder une trace de vos lectures, car la plupart du
temps, vous n’en aurez que peu de souvenirs au bout d’un mois.

Plus généralement, pensez à prendre en note **tout** ce que vous pensez,
à n’importe quel moment, à propos de votre mémoire. Ce qui implique
d’avoir son portable sous la main pour noter des choses pendant que vous
réfléchissez dans le métro, ou bien un carnet à côté de son lit pendant
les nuits d’insomnie (ce n’est pas une excuse pour ne pas essayer de
vous déconnecter de votre travail de mémoire autant que possible une
fois la journée terminée). Le principe du research log ou carnet de bord
est de centraliser quelque part toutes vos bonnes idées, vos réflexions,
vos esquisses de plan de mémoire ou de section, *etc*.

{{% callout note %}} Cette pratique des mini-notes de lecture et du
research log s’articule bien avec l’usage de Zotero (voir
[ci-dessous](#zotero)). {{% /callout %}}

### Zotero, la boîte à (quasi-)tout faire {#zotero}

[Zotero](https://www.zotero.org/), qu’est-ce que c’est :

-   C’est un outil pour créer des bibliographies (son usage le plus
    connu). A partir des références que vous avez intégrées dans Zotero,
    vous pouvez générer des bibliographies en document texte selon le
    style bibliographique de votre choix (possibilité également de créer
    un `.bib` pour ceux qui utilisent
    [*LaTeX*](https://www.latex-project.org/). Vous pouvez vous en
    servir dans word, en l’utilisant dans le texte pour citer des
    références (en auteur-date ou en note de bas de page), ce qui vous
    permet de créer une bibliographie avec toutes les références que
    vous avez citées à la fin du document.

-   C’est un outil pour récupérer facilement des références et des PDF
    sur internet. Il existe des connecteurs pour quasiment chaque
    navigateur, et une fois sur Google Scholar, JSTOR, Google Books,
    etc, vous pouvez récupérer en un clic les métadonnées, ainsi que le
    PDF s’il est accessible.[^5]

-   Zotero permet d’organiser votre matériel/corpus de manière plus
    efficace et centralisée.

    -   L’utilisation de Zotero permet de renommer automatiquement (ou
        en un clic) vos pdf, et ainsi de les avoir tous regroupés au
        même endroit, et de pouvoir naviguer facilement dans vos pdf
        grâce au moteur de recherche intégré à Zotero (recherche par
        auteur, par titre, par revue, par tags, et même par contenus des
        pdf).

    -   Il est également possible d’ajouter des marqueurs pour chaque
        référence, ce qui permet de donner quelques mots clés aux
        documents que vous avez extraits, et de pouvoir naviguer plus
        facilement dans votre corpus par la suite.

    -   Vous pouvez également connecter les références entre elles, mais
        surtout vous pouvez associer une ou plusieurs notes à chaque
        référence. C’est une manière efficace d’écrire vos notes de
        lecture, et de les avoir directement associées au texte dont il
        est question.

    -   Les notes ne doivent pas nécessairement être connectées à une
        référence. Il est ainsi possible de prendre en note toutes vos
        idées/réflexions/arguments pour votre mémoire. Chaque fois où
        vous voulez noter des réflexions, ouvrez une nouvelle note sur
        Zotero. Ces notes seront donc classées par date, et vous pourrez
        leur adjoindre des “marqueurs” suivant ce dont elles parlent (en
        plus de pouvoir recourir au moteur de recherche pour chercher
        dans le contenu des notes).

-   Dans sa version beta, Zotero intègre désormais un lecteur de PDF.
    Vous pouvez donc ouvrir directement un pdf dans Zotero, le surligner
    et le commenter. Ces commentaires sont sauvegardés dans Zotero mais
    pas dans le pdf, ce qui vous permet de faire circuler le pdf à des
    collègues sans faire circuler vos notes personnelles.

-   Enfin, Zotero est également un outil de gestion de Flux RSS, outil
    essentiel pour faire de la veille (plus d’information
    [ici](https://www.zotero.org/support/fr/feeds)).

Il existe une documentation assez détaillée sur Zotero, ainsi que
différent blogs avec des suggestions d’utilisation et des bonnes
pratiques (et notamment un [blog
francophone](https://zotero.hypotheses.org/)).

### La recherche et l’écriture d’un mémoire ne sont pas une activité solitaire

Même s’il implique beaucoup de tâche solitaire, puisqu’il s’agit de
*votre* recherche et de *votre* mémoire, il ne faut pas négliger
l’aspect social et collectif de ce travail. Pensez à solliciter votre
directeur ou directrice de mémoire : il ne s’agit pas de le/la harceler,
mais de faire en sorte qu’ils ou elles lisent vos premiers brouillons,
et surtout de lui écrire dès que vous avez quelques questions.

Tout aussi important : pensez à partager vos réflexions, idées et
difficultés avec les autres étudiants. N’hésitez pas à organiser des
sessions de discussions collectives et de relecture. C’est le meilleur
moyen de progresser (votre travail sera discuté et relu, mais vous
apprendrez également beaucoup en faisant la même chose sur le travail
des autres).

## L’écriture du mémoire

{{% callout note %}} Au-delà des conseils ci-dessous, vous trouverez de
nombreuses ressources pour la rédaction scientifique sur le site
d’[Ecritac, Tactiques pour l’écriture
académique](https://ecritac.hypotheses.org/). Ecritac partage notamment
en ligne une [bibliographie
Zotero](https://www.zotero.org/groups/2529470/ecritac) avec plus de 500
références (livres, articles, podcasts, billets de blog) autour des
différentes facettes de la recherche et de l’écriture scientifique.
{{% /callout %}}

### L’organisation du travail d’écriture

En ce qui concerne le rythme de l’écriture et l’organisation de cette
écriture, il n’y a pas de règles d’or :

-   Chacun a son rythme, chacun est capable d’écrire plus ou moins de
    pages en une journée/semaine. A vous d’apprendre à vous connaître et
    d’organiser l’écriture du mémoire en conséquence.

-   Chacun a son organisation : certains écrivent à partir d’une idée
    très large, complètent par des recherches pendant l’écriture,
    réécrivent plusieurs fois. D’autres font un plan très serré, se
    construisent une idée très précise de ce qu’ils veulent écrire, puis
    écrivent un premier jet déjà solide.

Quels que soient le rythme et l’organisation de l’écriture, un mémoire
rendu ne peut être un premier jet. Laissez-vous le temps d’une
réécriture, et d’une sérieuse relecture. Ne finissez pas votre mémoire
trois jours avant le rendu !

### Quel type de contribution : synthèse ou originalité ?

Il n’est pas attendu de véritable contribution à la recherche à
proprement parler : vous êtes encore en M2 et les évaluateurs en sont
bien conscients. Il s’agit d’abord de témoigner d’une capacité à offrir
une revue de littérature sur un sujet, à montrer une certaine
connaissance des problématiques. Il ne vous est pas demandé de faire une
contribution originale à la recherche.

Cela ne veut pas dire que votre mémoire ne peut pas comporter une
certaine part d’originalité. Où peut se trouver l’originalité ?

-   dans l’objet étudié:

    -   par l’objet en tant que tel ;

    -   du fait de la perspective adoptée pour étudier cet objet ;

    -   du fait de la période/zone géographique choisie ;

-   dans les matériaux utilisés (archives/correspondances,
    interviews…).

Il n’y pas forcément de nécessité d’avoir une thèse forte et originale
dans votre mémoire, même s’il faut avoir un fil conducteur, un argument
à défendre.

### Structure du mémoire

Il est important d’avoir une vision “souple” de la structure : ce n’est
pas une dissertation. Ne vous imposez pas des règles inutiles de deux ou
trois parties, de thèse/antithèse/synthèse ou autre carcan de ce genre.

Différents types de structure peuvent être envisageables :

-   Structure chronologique ;

-   structure qui présente les différents camps en présence (tâchez dans
    ce camp de ne pas vous contenter de présenter les différents camps,
    mais de faire avancer l’argumentation et de donner un certain
    dynamisme à cette présentation) ;

-   structure en fonction des différentes controverses étudiées ;

-   structure par méthode et sources mobilisées.

De nombreux choix de structure sont possibles et la flexibilité est de
mise. L’important est la cohérence d’ensemble, le fait que les parties
s’articulent entre elles et qu’elles vous permettent de faire avancer
votre argument.

### Longueur du mémoire

C’est souvent une angoisse au début de l’écriture : “ai-je assez de
choses à dire? Mon mémoire ne sera-t-il pas trop court?”. En général,
c’est plutôt l’inverse qui se produit.

L’écriture d’un mémoire implique la maîtrise de votre sujet mais une
certaine capacité à synthétiser, à passer rapidement sur certains
arguments/faits/éléments d’analyse, s’ils sont sourcés. Il n’y a pas de
critère de taille : personne ne dira que votre travail est génial car il
dépasse les 100 pages.

Sachez couper, sachez aller droit au but, tout en utilisant habilement
références, annexes et notes de bas-de-page pour donner plus de détails.
Lors de la relecture de votre mémoire, efforcer vous de couper les
longueurs et de rendre le texte plus dynamique.

### Quelques conseils d’écriture

#### Soigner son argumentation

Il est important d’étayer tous ses arguments. Dès que l’on affirme
quelque chose, il est nécessaire de le justifier :

-   par un raisonnement logique approprié ;

-   par une référence (il faut de citer dès que vous vous référez à une
    source, ou de trouver des sources qui appuient ce que vous dîtes si
    vous avancez un argument) ;

-   en exhibant des preuves (données statistiques, citations, passage
    d’interview…).

#### Savoir être direct

Il est important d’éviter autant que possible le “méta-texte” :

-   ne pas annoncer ce qui est “intéressant”, vous devez montrez que
    c’est intéressant ;

-   “il est évident que…” : Rien n’est évident !

-   les effets d’annonces (“on va faire…”, “nous allons montrer
    que…”, “nous allons d’abord nous intéresser à…”) ;

-   Faîtes, n’essayez pas : “je vais essayer de motnrer que…”, “je
    m’efforce de démontrer que…”.

#### Soignez le style

Il y a plusieurs “règles” de style à garder en tête quand l’on écrit.
Ces règles ne sont pas absolues, elles ne fonctionnent pas à tous les
coups, et certaines peuvent parfois rentrer en contradiction. Mais elles
sont importantes à garder en tête pour prendre du recul sur son
écriture, et savoir repérer là où l’on pèche.[^6]

1.  Une phrase commence par un sujet et un verbe autant que faire se
    peut.

    -   ce qui implique la forme active autant que possible (si vous
        utilisez la forme passive, ayez conscience que c’est parce que
        vous voulez mettre en avant quelque chose) ;

    -   les sujets des phrases (surtout quand on fait de l’histoire)
        doivent être autant que possible des individus, des sujets
        agissant. 

2.  Vérifiez que le sujet de la phrase est toujours évident : “Esther
    Duflot recourt alors à l’expérience aléatoire. **Elle** s’oppose aux
    expériences de laboratoire”.

3.  Évitez les verbes “être”, “avoir”, “faire”, “dire” ; utilisez des
    verbes avec une signification plus précise.

4.  Assurez-vous de l’enchaînement logique entre les phrases :

    -   ce qui commence la phrase n+1 doit être ce qui termine la phrase
        n ;

    -   utiliser les coordinateurs logiques: “donc”, “par conséquent”,
        “cependant”, “bien que…”Jacques Drèze, à son retour des
        Etats-Unis, crée le Center for Operations Research and
        Econometrics (CORE). Le centre permet **alors** d’accueillir des
        chercheurs dont les centres d’intérêts convergent vers des
        thématiques communes. La théorie de l’équilibre général occupera
        **ainsi** une place centrale au sein du CORE”.

5.  Utilisez les notes de bas de page pour sourcer/étayer des propos,
    sans casser la “dynamique” du texte principal.

6.  Abandonner vos velléités littéraires. “Jacques Drèze, à son retour
    du pays de l’Oncle Sam, se donna corps et âmes (car oui, il était
    habité par plusieurs âmes : l’amour de l’axiomatique et sa dévotion
    au projet d’une Europe unie par la Science) à la création de l’œuvre
    de sa vie : le Center for Operations Research and Econometrics
    (CORE). Le centre constitua un hâvre, un cénacle, une pléiade – que
    dis-je : un Éden ! – pour les chercheurs mathématiciens en mal de
    reconnaissance dans leurs contrées respectives.”

7.  Ne pas être jargonneux tout en maîtrisant le vocabulaire technique.
    “Répliquant l’ontologie post-hayékienne des cycles d’affaires, Lucas
    renverse l’épistémologie économétrique de la macroéconomie de la
    synthèse, en recourant à un paradigme kuhnien hybride, car
    a-réaliste et non-poppérien”.

8.  Les citations ne s’expliquent pas toutes seules : il faut les
    commenter  !

#### La relecture, l’étape indispensable

De manière générale : ne surestimez pas votre lecteur. Concrètement, il
s’agit d’enseignants-chercheurs qui vont devoir lire beaucoup de
mémoires. Autrement dit, ce n’est pas à eux de “tout” faire pour
comprendre ce que vous avez voulu “réellement” dire. Ce que vous voulez
dire doit être explicité clairement, et donc compréhensible dès la
première lecture. Notamment, le sens des termes important (récurrents)
dans votre mémoire doit être toujours explicité. 

N’hésitez pas à vous faire relire par d’autres étudiants, pour vérifier
si votre texte est compréhensible (surtout l’introduction). 

### Pour les curieux : L’écriture et ses outils

Il est probable que vous êtes désormais coutumier de l’utilisation de
libre office ou de word. Ces logiciels offrent une panoplie d’outils qui
permettent de rédiger des mémoires (stylage du document, création de
tables des matières, etc.). Néanmoins, ces logiciels ont quelques
défauts :

-   Faible portabilité (tout un tas d’erreurs de formatage peuvent se
    glisser dans le document si vous le transmettez à un
    co-auteur/lecteur qui utilise une autre version, un autre système
    d’exploitation…)

-   Instabilité dans le temps (changer de version de word peut
    introduire des problèmes dans la lecture de documents écrits avec
    les versions précédentes)

-   effet boîte noire pour certaines fonctions : il est parfois très
    compliqué sur Word ou libreOffice de comprendre pourquoi l’on arrive
    pas à réaliser telle ou telle chose. Le fait que word soit sous
    licence privée renforce cela.

Il existe tout un tas d’outils alternatifs, en partie développés pour
les chercheurs. Ces outils ont en commun de séparer l’écriture du texte,
de son formatage. La formatage se fait par l’écriture de fonctions et
lignes de code.

En économie, l’outil le plus répandu, tant pour écrire ses articles, son
mémoire, sa thèse que ses slides, est
[LaTeX](https://www.latex-project.org/). LaTeX est un logiciel libre,
qui permet de formater vos textes de manière simple et prévisible, une
fois maîtrisées les commandes de base. Vous n’aurez besoin que d’une
demi-journée d’initiation pour pouvoir commencer à écrire des documents
sur LaTeX (voir par exemple ce
[tutoriel](https://nicolasj.developpez.com/articles/latex/introduction/)).
Il existe également un outil de collaboration en ligne pour LaTeX qui a
l’avantage d’être assez agréable à utiliser (même si vous écrivez seul)
et qui vous dispense d’installer les logiciels nécessaires sur votre
ordinateur personnel : [Overleaf](https://fr.overleaf.com/).

Il existe une autre approche, un peu plus difficile à prendre en mains,
mais qui offre de nombreux avantages (voir une description complète
[ici](https://programminghistorian.org/fr/lecons/redaction-durable-avec-pandoc-et-markdown)
ou
[ici](https://www.arthurperret.fr/2021-09-21-ecriture-academique-format-texte.html)).
Plutôt que de passer directement par LaTeX, vous pouvez écrire et coder
en [Markdown](https://www.markdownguide.org/basic-syntax/), un langage
extrêmement simple utilisé au départ pour produire des pages *html*.
Grâce à [pandoc](https://pandoc.org/), vous pouvez ensuite transformer
votre fichier markdown en page html, en pdf (pandoc utilise LaTeX pour
cela), ou même en document word. LaTeX, tout comme cette seconde
approche, permettent une intégration étroite avec Zotero (voir les
explications [ici](https://zotero.hypotheses.org/2258)).

Il est évident que ces approches ont un coût d’entrée pour pouvoir se
les approprier, tant pour en acquérir les bases, que pour trouver des
solutions aux petites erreurs qui pourront être nombreuses dans les
premiers mois d’utilisation. Elles valent néanmoins le coup de s’y
intéresser, car elles peuvent constituer un gain de temps certains à
plus long terme, et permettent d’acquérir des compétences dont le
domaine d’application s’avèrent plus large que la maîtrise des
différents onglets de la version 2016 de word (écriture de page web,
édition de revues et livres, maîtrise plus approfondie des styles
bibliographiques, initiation à l’utilisation de la ligne de commande,
etc…).

## Bibliographie

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-backhouse1992a" class="csl-entry">

Backhouse, Roger E. 1992. “How Should We Approach the History of Economic Thought, Fact, Fiction or Moral Tale?” *Journal of the History of Economic Thought* 14 (1): 18–35. <https://doi.org/10.1017/S1053837200004375>.

</div>

<div id="ref-backhouse2001a" class="csl-entry">

———. 2001. “How and Why Should We Write the History of Twentieth-Century Economics?” *Journal of the History of Economic Thought* 23 (2): 243–51.

</div>

<div id="ref-collini1988a" class="csl-entry">

Collini, Stefan. 1988. “‘Discipline History’ and ‘Intellectual History’ Reflections on the Historiography of the Social Sciences in Britain and France.” *Revue de Synthèse* 109 (3-4): 387–99. <https://doi.org/10.1007/BF03189137>.

</div>

<div id="ref-emmett2014" class="csl-entry">

Emmett, Ross B. 2014. “Defending the History of Economic Thought.” *History of Political Economy* 46 (3): 539–40. <https://doi.org/10.1215/00182702-2796400>.

</div>

<div id="ref-fontaine2016" class="csl-entry">

Fontaine, Philippe. 2016. “Other Histories of Recent Economics: A Survey.” *History of Political Economy* 48 (3): 373–421. <https://doi.org/10.1215/00182702-3638607>.

</div>

<div id="ref-forget2005" class="csl-entry">

Forget, Evelyn L. 2005. “Same View, Many Lenses.” *History of Political Economy* 37 (2): 205–10. <https://doi.org/10.1215/00182702-37-2-205>.

</div>

<div id="ref-hands1997" class="csl-entry">

Hands, D. Wade. 1997. “Conjectures and Reputations: The Sociology of Scientific Knowledge and the History of Economic Thought.” *History of Political Economy* 29 (4): 695–739.

</div>

<div id="ref-lapidus2019" class="csl-entry">

Lapidus, André. 2019. “Bringing Them Alive.” *The European Journal of the History of Economic Thought* 26 (6): 1084–1106. <https://doi.org/10.1080/09672567.2019.1682022>.

</div>

<div id="ref-passmore1965" class="csl-entry">

Passmore, John. 1965. “The Idea of a History of Philosophy.” *History and Theory* 5: 1–32. <https://doi.org/10.2307/2504117>.

</div>

<div id="ref-rorty1984a" class="csl-entry">

Rorty, Richard. 1984. “The Historiography of Philosophy: Four Genres.” In *Philosophy in History: Essays in the Historiography of Philosophy*, 49–75. Cambridge ; New York: Cambridge University Press.

</div>

<div id="ref-seidman1983a" class="csl-entry">

Seidman, Steven. 1983. “Beyond Presentism and Historicism: Understanding the History of Social Science.” *Sociological Inquiry* 53 (1): 79–91. <https://doi.org/10.1111/j.1475-682X.1983.tb01167.x>.

</div>

<div id="ref-stapleford2017a" class="csl-entry">

Stapleford, Thomas A. 2017. “Historical Epistemology and the History of Economics: Views Through the Lens of Practice.” In *Symposium on the Historical Epistemology of Economics*, 35A:113–45. Research in the History of Economic Thought and Methodology. Emerald Publishing Limited. <https://doi.org/10.1108/S0743-41542017000035A007>.

</div>

<div id="ref-thomas2017" class="csl-entry">

Thomas, William. 2017. “Scientists’ Imagined Pasts and Historians’ Appreciation of Scientific Thought.” *Isis* 108 (4): 830–35. <https://doi.org/10.1086/695605>.

</div>

<div id="ref-weintraub1999a" class="csl-entry">

Weintraub, E. Roy. 1999. “How Should We Write the History of Twentieth-Century Economics?” *Oxford Review of Economic Policy* 15 (4): 139–52. <https://doi.org/10.1093/oxrep/15.4.139>.

</div>

<div id="ref-weintraub2005" class="csl-entry">

———. 2005. “Misusing History: A Minisymposium.” *History of Political Economy* 37 (2): 177–78.

</div>

<div id="ref-wilson2017" class="csl-entry">

Wilson, Adrian. 2017. “Science’s Imagined Pasts.” *Isis* 108 (4): 814–26. <https://doi.org/10.1086/695603>.

</div>

<div id="ref-winch2018" class="csl-entry">

Winch, Donald. 2018. “Intellectual History and the History of Economic Thought: A Personal Account.” *Journal of Interdisciplinary History of Ideas* 6 (12).

</div>

</div>

[^1]: Voir également le *Routledge Handbook* sur la pensée économique
    dans le monde \[@routledg2015\].

[^2]: Sur les études sociales des controverses scientifiques, voir le
    livre de @gingras2014 avec de nombreuses études de cas
    intéressantes.

[^3]: Sur l’étude des conférences en économie, voir le double numéro
    spécial parut dans la *Revue d’Economie Politique:
    <https://www.cairn.info/revue-d-economie-politique-2021-4.htm> et
    <https://www.cairn.info/revue-d-economie-politique-2021-5.htm>.*

[^4]: Voir la typologie et les outils intéressants mis en avant par
    @allisson2020 sur la question de l’héritage intellectuel.

[^5]: A noter que Zotero peut également permettre de stocker des pages
    webs (comme des articles de presse ou des billets de blogs).

[^6]: Pour aller plus loin sur ce sujet, il existe quelques ouvrages
    intéressant (en anglais) sur le style d’écriture \[@hayot2014;
    @sword2012\].
