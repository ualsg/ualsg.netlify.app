---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Geospatial and urban data science journals"
subtitle: "List of relevant journals with their latest metrics"
summary: "List of relevant journals with their latest metrics"
authors: [filip]
tags: [journals, guides]
categories: []
date: 2020-07-06T08:56:41+08:00
lastmod: 2020-07-06T08:56:41+08:00
featured: false
draft: false
exclude_jquery: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by [chuttersnap](https://unsplash.com/@chuttersnap) on [Unsplash](https://unsplash.com/photos/q3o7xqYQtes)"
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

It is that time of the year: the journal impact factors have been published.

I maintain a list of relevant journals, which I have decided to publish in this article together with their latest metrics, hopefully helping fellow researchers to have a reference list and choose where to publish their next paper.

For more information about how the journals were selected and explanations about the columns, [see below](#selection-of-journals).

## List of journals with metrics 

{{< journals >}}

#### Notes
* The column IF refers to impact factors from 2019, published in 2020. The same goes for SJR.
* The column "Change" indicates the percentage change of the IF from 2018 to 2019.

## Selection of journals

The key question is what is a geospatial/urban data science journal?
It depends who you ask.

While lists such as this one will inevitably be a tad subjective (mostly because the fields have no clear boundaries and people focus on different topics), I trust that I have covered pretty much all the relevant journals in [what we do](/).
Many of them are from the selection published in my 2016 IJGIS paper [_A scientometric analysis of selected GIScience journals_](https://doi.org/10.1080/13658816.2015.1130831), which has evolved since then following the convergence of disciplines.

Some of these journals, such as [PLOS ONE](https://journals.plos.org/plosone/) and the [Science of the Total Environment](https://www.journals.elsevier.com/science-of-the-total-environment), are "mega-journals" publishing papers on a wide range of topics and have published articles that are relevant in our domain.
Further, there are some predominantly remote sensing journals included.
Still, they are known to publish geo-stuff relevant to us (e.g. on standardisation in 3D city modelling, our main interest), so they are included as well.

While there are some journals with a borderline IF, I have included them for multiple reasons. Some of them have a relatively low IF, but it is increasing at a higher rate than the field's average, thus, I would consider them as "rising stars" and "honourable mentions".
Some have a low IF, but their _aims and scope_ are very related.
Further, I included also some journals that are not indexed yet, but which are well worth considering.

## Metrics

The journal impact factor (IF) is a key metric in scientometrics to quantify the importance (impact) of a journal.
It is [easy to understand](https://en.wikipedia.org/wiki/Impact_factor), but also subject to [controversies](https://en.wikipedia.org/wiki/Impact_factor#Criticisms).
IFs are published by Clarivate in the [Journal Citation Reports (JCR)](https://clarivate.com/webofsciencegroup/solutions/journal-citation-reports/), based on the data from [Web of Science](https://www.webofknowledge.com).
They are available yearly, and are published in June for the last year (e.g. the JCR 2020 report containing IFs for 2019 was published in June 2020). 
It is important to note that it is challenging to compare metrics across disciplines, due to the different sizes of fields, among other reasons.
For example, 1.911 is considered to be a very high impact factor in mathematics, but nothing special in cell biology or immunology.
This disparity is why rankings of journals within categories/fields/disciplines are essential.

[SCImago Journal Rank (SJR)](https://www.scimagojr.com) is another metric, and it is gaining prominence. 
It quantifies the journal's influence, but differently: it expresses the average number of weighted citations received in the selected year by the documents published in the journal in the three previous years (longer than the IF).
Another difference from the IF is that SJR is derived from Elsevier's [Scopus](https://www.scopus.com/), which is more inclusive.
A focus of SJR is on understanding the prestige of a journal within a subdiscipline, and it is expressed in quartiles. 
For example, a Q1 (first quartile) journal is one that has the SJR in the top 25% of the journals in one or more of its subdisciplines.
Read more [here](https://academia.stackexchange.com/a/116470).

Finally, it is evident that such metrics are in many ways flawed, but we cannot pretend they are not important and well ingrained in academia, and used as a deciding factor in promotions.


## Some observations

Unsurprisingly, most journals have their IF increased since last year.
Some of them raised by more than 50%.

While some journals have their IF steadily increasing, there is a lot of fluctuation on a year-by-year basis for some.
Therefore, I am sure that this list will look different next year.

A few journals are indexed for the first time.
For example, [PeerJ Computer Science](https://peerj.com/computer-science/) and the [International Journal of Urban Sciences](https://www.tandfonline.com/toc/rjus20/current) gained their impact factor for the first time.

## FAQ

### Why some journals have no IF and/or SJR?

Some journals, such as the [Open Geospatial Data, Software and Standards](https://opengeospatialdata.springeropen.com), are not indexed (yet), even though they publish high-quality work and are managed by a reputable publisher and editorial board.
This void is normal for new journals.
I believe that it is just a matter of time when these journals become indexed.


### What if there are multiple categories?

In both JCR and SJR a journal can be assigned to multiple categories.
For example, [CEUS](https://www.journals.elsevier.com/computers-environment-and-urban-systems) is part of four subdisciplines, e.g. urban studies.
A journal will have a different ranking in each subdiscipline it is part of.
SJR takes the best ranking.
However, I noticed that a Q1 journal would usually be Q1 in all its subdisciplines.


### What about ranks from IF/JCR?

The quartiles in the list are sourced from SJR.
Technically, you can also get the rank (quartile) from JCR, by checking the IF of the journal and its position in the respective category.
For example, [IJGIS](https://www.tandfonline.com/toc/tgis20/current) is part of two categories over there (Physical Geography and Computer Science).
In the former, it ranked as 11th out of 50 journals in the category, so I guess that means Q1, but I haven't seen that being used often.
Also, do note that JCR uses citation data from a more exclusive database.
Most of the journals above are in Q1 in SJR, but not all of them will be Q1 in JCR.
