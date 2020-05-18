---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Large-scale 3D geospatial data for urban analytics"
summary: "Augmentation of 3D city models with machine learning techniques"
authors: [filip, yoong-shin, li-min]
tags: [machine learning, 3d gis]
categories: []
date: 2019-10-01T21:11:51+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "3D city model of Hamburg, Germany. Open dataset. Source: Biljecki F, Dehbi Y (2019). Raise the roof: towards generating LoD2 models without aerial surveys using machine learning. _ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci._, IV-4/W8: 27-34."
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This three-year project is focused on devising a method to estimate individual building heights in the absence of traditional measurements such as lidar, to generate 3D city models solely from building footprints on a very large scale spanning scores of countries.
It is funded by the National University of Singapore, and it started in late 2019.

The project seeks to build on top of the method previously presented by the project PI, described in the journal paper:

> Biljecki, F., Ledoux, H., & Stoter, J. (2017). Generating 3D city models without elevation data. _Computers, Environment and Urban Systems_, 64, 1–18. doi: [10.1016/j.compenvurbsys.2017.01.001](http://doi.org/10.1016/j.compenvurbsys.2017.01.001)

The work included developing a regression model (random forest) to estimate the heights of buildings from their footprints, using only 2D datasets, without remotely sensed data.
This project aspires to scale the method to achieve global coverage and derive heights of individual buildings around the world.
It will also investigate the potential addition of remotely sensed data.
The targeted deliverables are a list of predicted heights attached to all buildings in OpenStreetMap, and a 3D building model in [CityJSON](https://cityjson.org) in [LoD1](https://doi.org/10.1016/j.compenvurbsys.2016.04.005) generated using the OSM footprints and predicted heights, to facilitate use in the geospatial domain and urban analytics.

This ongoing project also includes other research tasks, such as:
* Developing a method to assess the global building completeness in OSM.
* Understanding the quality of heights already available in OSM, which can be used as training data.
* Exploring use cases relying on the availability of such dataset.
* Using machine learning to infer the roof type of buildings, leading to the generation of highly detailed building models (as in the image in the header above). This portion has already been investigated, and a [paper](/publication/2019-inferring-roof-type/) has been published.



