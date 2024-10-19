---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "New paper: Nighttime Street View Imagery"
subtitle: "Sustainable Cities and Society publishes our work on a new perspective for sensing urban lighting landscape."
summary: "Sustainable Cities and Society publishes our work on a new perspective for sensing urban lighting landscape."
authors: [admin]
tags: [paper, nighttime, ntl, computer vision, street view]
categories: []
date: 2024-10-19T09:43:22+08:00
lastmod: 2024-10-19T09:43:22+08:00
featured: false
draft: false
show_related: true
pager: true

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

---

We are glad to share our new paper:

> Fan Z, Biljecki F (2024): Nighttime Street View Imagery: A new perspective for sensing urban lighting landscape. Sustainable Cities and Society, 116: 105862. [<i class="ai ai-doi-square ai"></i> 10.1016/j.scs.2024.105862](https://doi.org/10.1016/j.scs.2024.105862) [<i class="far fa-file-pdf"></i> PDF](/publication/2024-scs-night-svi/2024-scs-night-svi.pdf)</i> <i class="ai ai-open-access-square ai"></i>

This research was led by {{% mention "zicheng" %}}.
Congratulations on his first PhD journal publication! :raised_hands: :clap:

The dataset has been released openly at [GitHub](https://github.com/fzc961020/Nighttime-SVI).

![](1.png)

![](2.png)

### Highlights

+ Street View Imagery (SVI) is taken almost exclusively during daytime, ignoring the urban nightscape.
+ Elucidation of data collection and usability of such imagery during night.
+ Exploring the profound correspondence between daytime SVI and nighttime SVI.
+ Identifying nighttime SVI as viable complement for Nighttime Lights satellite imagery.
+ Position that nighttime SVI is a latent but valuable urban dataset.

![](3.png)

![](4.png)


### Abstract

> Urban lighting reflects nocturnal activities and it is traditionally observed using Nighttime Lights (NTL) satellite imagery. Few studies systematically measure the nightscape from a human perspective. This study brings a new paradigm — urban lighting sensing via Nighttime Street View Imagery (SVI). The paradigm draws on the accomplishments of (daytime) SVI and gives attention to its ignored nighttime counterpart. We put forward this idea by manually collecting 2,831 nighttime SVIs across various urban functional areas in Singapore. We investigated their values by developing a use case for clustering nighttime lighting patterns. To mitigate the scarcity of nighttime SVI, deep learning regression models were trained to predict nighttime brightness based on corresponding daytime SVIs obtained from widely available sources. The results were compared with brightness data derived from satellite imagery, to affirm the novelty and uniqueness of nighttime SVI. As a result, there are 7 lighting patterns within the collected nighttime SVI, distinct in lighted spot features and total brightness. The identified patterns effectively characterize different urban function scenarios. The best trained brightness prediction model performs well in revealing the city-scale lighting landscape. The SVI-predicted brightness shows a distribution similar to the brightness from satellite imagery and complements it in urban areas with complex vertical lighting structures. This study demonstrates the potential of nighttime SVI as a valuable data source for mapping urban lighting and activities, offering advantages over satellite data. The proposed paradigm contributes significantly to cross-modal information mining in urban studies and has potential applications in scenarios such as light pollution mitigation and crime prevention.

![](5.png)

![](6.png)

### Paper 

For more information, please see the [paper](/publication/2024-scs-night-svi/).

[![](page-one.png)](/publication/2024-scs-night-svi/)

BibTeX citation:
```bibtex
@article{2024_scs_nightSVI,
 author = {Fan, Zicheng and Biljecki, Filip},
 doi = {10.1016/j.scs.2024.105862},
 journal = {Sustainable Cities and Society},
 pages = {105862},
 title = {Nighttime Street View Imagery: A new perspective for sensing urban lighting landscape},
 volume = {116},
 year = {2024}
}
```
