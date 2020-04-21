---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Towards generating LoD2 models without aerial surveys using machine learning"
subtitle: ""
summary: "The paper deals with inferring the type of roof from LOD1 models, potentially contributing to a broader context of a workflow of generating LoD2 models bypassing traditional approaches."
authors: [admin]
tags: [machine learning, lod2, geographic data science, 3D geoinfo]
categories: []
date: 2019-09-23T18:35:16+08:00
lastmod: 2019-09-23T18:35:16+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Open 3D city model of Hamburg, Germany in LoD2 (including roof types). We investigated whether we can infer the type of roof without traditional approaches such as photogrammetry."
  focal_point: ""
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [3d-machine-learning]
---

{{< figure src="featured.png" title="Open 3D city model of Hamburg, Germany in LoD2 (including roof types). We investigated whether we can infer the type of roof without traditional approaches such as photogrammetry." numbered="false" lightbox="true" >}}

We published a new paper:

> Biljecki F, Dehbi Y (2019): Raise the roof: towards generating LoD2 models without aerial surveys using machine learning. _ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci._ IV-4/W8:27-34. [<i class="ai ai-doi-square ai"></i> 10.5194/isprs-annals-IV-4-W8-27-2019](https://doi.org/10.5194/isprs-annals-IV-4-W8-27-2019) [<i class="far fa-file-pdf"></i> PDF](/publication/2019-inferring-roof-type/2019-inferring-roof-type.pdf) <i class="ai ai-open-access-square ai"></i>

The paper deals with inferring the type of roof from LoD1 models, potentially contributing to a broader context of a workflow of generating LoD2 models bypassing traditional approaches.

The work is a continuation of the [previous work on generating LoD1 models from building footprints without elevation measurements](https://doi.org/10.1016/j.compenvurbsys.2017.01.001), by inferring the heights of buildings solely from 2D data (using Random Forest regression). 

We have used 10 different predictors, e.g. building function, building height, and number of OpenStreetMap amenities in the neighbourhood, some of which are more useful than others. 
For example, the vertical extent of the building (storeys and height) may give a good indication about the roof type:

{{< figure src="roof_types_vertical_hist.png" title="The vertical extent of the building part gives an indication of the roof type. The plot shows a 0.1% random subset of our test dataset." numbered="false" lightbox="true" >}}

For training and testing purposes we have used the 3D city model of Hamburg, Germany. 
In the end we have achieved an accuracy of 85% in predicting the type of the roof.
We also carried out another classification for predicting whether a roof is flat or not (with 92% accuracy).

The list of features we have used and their importance (in both determining the roof type and in the binary classification whether a roof is flat or non-flat) is included below:

{{< figure src="feature_importance_comparison.png" title="Feature importance of the two approaches. Some predictors are more important than others." numbered="false" lightbox="true" >}}

While we are happy how this work turned out and we made a progress, there is still a lot to be done in this topic (e.g. reconstructing the geometry of the roof), which we intend to tackle in future work.
Our roadmap at the moment looks like this:

{{< figure src="roadmap.png" title="Proposed pipeline from LoD0 footprints to LoD2 models without aerial survey measurements. For previous work (inferring heights of buildings from footprints, generating LoD1 models) see ([Biljecki et al., 2017](https://doi.org/10.1016/j.compenvurbsys.2017.01.001))." numbered="false" lightbox="true" >}}


For more information please see the [paper](/publication/2019-inferring-roof-type/) (open access <i class="ai ai-open-access-square ai"></i>).

[![](page-one.png)](/publication/2019-inferring-roof-type/)


BibTeX citation:
```bibtex
@article{2019_inferring_roof_type,
    author = {Biljecki, F and Dehbi, Y},
    doi = {10.5194/isprs-annals-IV-4-W8-27-2019},
    journal = {ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci.},
    pages = {27--34},
    title = {Raise the roof: towards generating LoD2 models without aerial surveys using machine learning},
    volume = {IV-4/W8},
    year = {2019}
}
```
