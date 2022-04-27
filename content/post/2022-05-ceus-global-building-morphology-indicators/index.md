---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "New paper: Global Building Morphology Indicators"
subtitle: "Our paper Global Building Morphology Indicators has been published on one of the leading journals - Computers, Environment and Urban Systems"
summary: "Our work on Global Building Morphology Indicators has been published on one of the leading journal - Computers, Environment and Urban Systems"
authors: [admin]
tags: [urban planning, GIScience, morphometrics, OpenStreetMap, GeoAI, spatial analysis]
categories: []
date: 2022-04-27T11:41:37+08:00
lastmod: 2022-04-27T11:41:37+08:00
featured: false
draft: true

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
---

We are pleased to share that our work on Global Building Morphology Indicators has been 
published on the Computers, Environment and Urban Systems. 

> Biljecki F, Chow YS (2022): Global Building Morphology Indicators. _CEUS_ XX(XX):
> [<i class="ai ai-doi-square ai"></i>10.1016/j.compenvurbsys.2022.101809](https://doi.org/10.1016/j.compenvurbsys.2022.101809) [<i class="far fa-file-pdf"></i> PDF](/publication/2022-ceus-global-building-morphology-indicators/2022-ceus-global-building-morphology-indicators.pdf)</i><i class="ai ai-open-access-square ai"></i>

In this paper, a systematic review were conducted to derive a list of commonly used building 
indicators that parameterise buildings' urban form. These may serve a kaleidoscopic set of 
topics, and introduce new derivative parameters, furthering possibility in the domain of urban 
studies. 

As the tools available for urban morphological analyses are scarce, we also contributed the tool for computing these building metrics by open-sourcing our source code. The [GBMI](https://github.com/ualsg/global-building-morphology-indicators) code repository could be found publicly accessible on GitHub. 

We also developed the GBMI dataset for list of randomly selected cities and countries from 
around the world. These datasets are hosted on Harvard Dataverse, and their download links are  listed below. 

|                 |          |      |         |             |             |             |             |             |
|-----------------|----------|------|---------|-------------|-------------|-------------|-------------|-------------|
| amsterdam       | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| ankara          | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| barcelona       | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| chennai         | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| delft           | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| greater\_london | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| kampala         | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| kinta           | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| kyoto           | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| lugano          | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| melbourne       | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| nairobi         | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| quito           | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| san\_francisco  | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| singapore       | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| toronto         | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| ulaanbaatar     | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |
| zagreb          | [building]() | [cell]() | [country]() | [admin\_div1]() | [admin\_div2]() | [admin\_div3]() | [admin\_div4]() | [admin\_div5]() |

### Abstract

The abstract follows.

> Characterising and analysing urban morphology is a continuous task in urban data science, environmental analyses, and many other domains.
As the availability and quality of data on them have been increasing, buildings have gained more attention.
However, tools and data facilitating large-scale studies, together with an interdisciplinary consensus on metrics, remain scarce and often inadequate.
We present Global Building Morphology Indicators (GBMI) --- a three-pronged contribution addressing such shortcomings:
(i) a comprehensive list of hundreds of building form multi-scale measures derived through a systematic literature review;
(ii) a methodology and tool for the computation of these metrics in a database suited for big data and comparative studies, and release the code freely and open-source; and
(iii) we carry out the computations using high performance computing, generating a public repository with data quantifying the form of urban areas around the world, and demonstrate their value with novel analyses comparing morphological parameters across cities.
GBMI introduces a formalised, structured, modular, and extensible method to compute, manage, and disseminate urban indicators at a large scale and high resolution, while the precomputed dataset facilitates comparative studies.
The theory and implementation traverse multiple scales: at the building level, both individual and contextual ones based on encircling buildings by multiple buffers, and aggregations at several hierarchical administrative levels and at multiple regular global high resolution grids.
Our open dataset, comprising billions of records on a growing scope of urban areas worldwide, is the most comprehensive instance of morphological data parametrising the individual building stock, supporting studies in urban analytics and a range of disciplines.


### Paper 

For more information, please see the [paper]
(/publication/2022-ceus-global-building-morphology-indicators/) (open 
access <i class="ai ai-open-access-square ai"></i>).

[![](page-one.png)](/publication/2022-ceus-global-building-morphology-indicators/)

BibTeX citation:
```bibtex
@article{2022_ceus_global_building_morphology_indicators,
 author = {Biljecki, Filip and Chow, Yoong-Shin},
 date-added = {2022-04-27T11:41:37+08:00},
 date-modified = {2022-04-27T11:41:37+08:00},
 doi = {10.1016/j.compenvurbsys.2022.101809},
 journal = {CEUS},
 number = {X},
 pages = {X},
 title = {Global Building Morphology Indicators},
 volume = {X},
 year = {2022}
}
```


