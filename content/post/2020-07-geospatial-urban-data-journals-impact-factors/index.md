---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Geospatial and urban data science journals"
subtitle: "List of relevant journals with their latest metrics"
summary: "List of relevant journals with their latest metrics"
authors: [filip]
tags: [journals, guide, gis, index, long reads, analysis]
categories: []
date: 2020-07-06T08:56:41+08:00
lastmod: 2021-01-01T08:56:41+08:00
featured: false
draft: false
exclude_jquery: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## Introduction

UAL maintains a list of relevant academic journals with their latest metrics which we hope might be of use to fellow researchers. Feel free to check out our other geospatial resources or opportunities to collaborate with us in the tabs above.

For more information about how the journals were selected and explanations about the columns, [see below](#selection-of-journals).

## List of journals with metrics (July 2020)

{{< journals >}}

#### Notes
* The column IF refers to impact factors from 2019, published in 2020. The same goes for SJR.
* The column "Change" indicates the percentage change of the IF from 2018 to 2019.

## Selection of journals

The key question is what is a geospatial/urban data science journal?
It depends on who you ask.

While lists such as this one will inevitably be a tad subjective (mostly because nowadays fields have no clear boundaries and people focus on different topics), I trust that I have covered pretty much all the relevant journals in [what we do](/).
Many of them are from the selection published in my 2016 IJGIS paper [_A scientometric analysis of selected GIScience journals_](https://doi.org/10.1080/13658816.2015.1130831), which has evolved since then following the increased convergence of journals and introduction of new ones.

Some of these journals, such as [PLOS ONE](https://journals.plos.org/plosone/) and the [Science of the Total Environment](https://www.journals.elsevier.com/science-of-the-total-environment), are "mega-journals" publishing papers on a wide range of topics and have published articles that are relevant in our domain.
Furthermore, some journals in the list are predominantly into remote sensing, but they are known to occasionally publish geo-stuff relevant to us (e.g. on standardisation in 3D city modelling, our main interest), so they are included as well.

## Metrics

The journal impact factor (IF) is a key metric in scientometrics to quantify the importance (impact) of a journal.
It is [easy to understand](https://en.wikipedia.org/wiki/Impact_factor), but it is often denounced and subject to [controversies](https://en.wikipedia.org/wiki/Impact_factor#Criticisms).
IFs are published by Clarivate in the [Journal Citation Reports (JCR)](https://clarivate.com/webofsciencegroup/solutions/journal-citation-reports/), based on the data from the [Web of Science](https://www.webofknowledge.com).
They are available yearly, and are published in June for the last year (e.g. the JCR 2020 report containing IFs for 2019 was published in June 2020). 
It is important to note that it is challenging to compare metrics across disciplines, due to the different sizes and characteristics of fields, among other reasons.
For example, 1.911 is considered to be a very high impact factor in mathematics, but the same number is nothing special in cell biology or immunology.
This disparity is why rankings of journals within categories/fields/disciplines are essential.
Metrics become more complicated with our field because it does not have a dedicated category, and journals may publish articles from a mix of disciplines.

[SCImago Journal Rank (SJR)](https://www.scimagojr.com) is another metric, and it is gaining prominence. 
It quantifies the journal's influence, but differently: it expresses the average number of weighted citations received in the selected year by the documents published in the journal in the three previous years (longer than the IF).
Another difference from the IF is that SJR is derived from Elsevier's [Scopus](https://www.scopus.com/), which is more inclusive.
A focus of SJR is on understanding the prestige of a journal within a subdiscipline, and it is expressed in quartiles. 
For example, a Q1 (first quartile) journal is one that has the SJR in the top 25% of the journals in one or more of its subdisciplines.
Read more [here](https://academia.stackexchange.com/a/116470).

Finally, it is evident that such metrics are in many ways flawed, but we cannot pretend they are not important and well ingrained in academia, and used as a deciding factor in promotions.

While the list contains some journals with a _borderline_ IF, I have included them for multiple reasons.
First, as noted above, the IF is not without flaws and it should not be given too much importance, and there have been solid papers published in low-IF journals.
Some have been known to publish high quality papers before, but for some reason their IF dropped in the past few years.
Second, while some of the journals have a relatively low IF, it is increasing at a higher rate than the field's average.
Thus, I would consider them as "rising stars" and "honourable mentions".
Third, some journals that have a low IF have very pertinent _aims and scope_, which cannot be ignored.
Finally, I included also some journals that are not indexed at all, but which are well worth considering.


## Some observations

Unsurprisingly, most journals have their IF increased since last year.
Some of them raised by more than 50%.

While some journals have their IF steadily increasing, there is a lot of fluctuation on a year-by-year basis for some.
Therefore, this list might look different next year.

A few journals are indexed for the first time.
For example, [PeerJ Computer Science](https://peerj.com/computer-science/) and the [International Journal of Urban Sciences](https://www.tandfonline.com/toc/rjus20/current) gained their impact factor for the first time.

## SciRev

[SciRev](https://scirev.org) is a website where researchers share their experience with the peer-review process of particular journals.
It can be quite useful to understand the efficiency and attitude of some editors and journals.
Before submitting your paper to a journal, I would encourage you to have a look at the website.

## FAQ

### Why do some journals in the list have no IF and/or SJR?

Some journals, such as the [Open Geospatial Data, Software and Standards](https://opengeospatialdata.springeropen.com), are not indexed (yet), even though they publish high-quality work and are managed by a reputable publisher and editorial board.
This void is common for new journals because it may take several years before a journal becomes indexed.

There is also the [Journal of Open Source Software](https://joss.theoj.org), which is not a typical journal and might not have an IF any time soon, but it could be considered relevant, and it is a journal we warmly recommend if you have released an open-source software that warrants a paper.

### Hey, why is __________________ not in the list?

Probably because we don't find it relevant, it has predatory practices, and/or it has a consistent record of editorial mishandling.

### What if a journal belongs to multiple categories in databases?

In both JCR and SJR a journal can be assigned to multiple subject areas.
For example, in SJR, [CEUS](https://www.journals.elsevier.com/computers-environment-and-urban-systems) is [part of four subdisciplines](https://www.scimagojr.com/journalsearch.php?q=23269&tip=sid&clean=0): Ecological Modeling, Environmental Science (miscellaneous), Geography, Planning and Development, and Urban Studies.
A journal will have a different ranking in each subdiscipline it is part of.
SJR takes the best ranking for the overall score.
However, I noticed that a Q1 journal would usually be Q1 in all subdisciplines it is part of.


### What about ranks from IF/JCR?

The quartiles in the list are sourced from SJR.
Technically, you can also get the rank (quartile) from JCR, by checking the IF of the journal and its position in the respective category.
For example, [IJGIS](https://www.tandfonline.com/toc/tgis20/current) is part of two categories over there (Physical Geography and Computer Science).
In the former, it ranked as 11th out of 50 journals in the category, so I guess that means Q1, but I haven't seen that being used often.
Also, do note that JCR uses citation data from a more exclusive database.
Most of the journals above are in Q1 in SJR, but not all of them will also be in Q1 in JCR.



