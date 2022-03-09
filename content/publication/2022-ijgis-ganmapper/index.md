---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'GANmapper: geographical data translation'
subtitle: ''
summary: ''
authors:
- abraham
- filip
tags: []
categories: []
date: '2022-03-07'
lastmod: 2022-03-05T14:43:51+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-03-05T06:43:51.469335Z'
publication_types:
- '2'
abstract: ''
publication: '*International Journal of Geographical Information Science*'
doi: 10.1080/13658816.2022.2041643
---
We present a new method to create spatial data using a generative adversarial network (GAN).
Our contribution uses coarse and widely available geospatial data to create maps of less available features at the finer scale in the built environment, bypassing their traditional acquisition techniques (e.g. satellite imagery or land surveying).
In the work, we employ land use data and road networks as input to generate building footprints and conduct experiments in 9 cities around the world.
The method, which we implement in a tool we release openly, enables the translation of one geospatial dataset to another with high fidelity and morphological accuracy. 
It may be especially useful in locations missing detailed and high-resolution data and those that are mapped with uncertain or heterogeneous quality, such as much of OpenStreetMap.
The quality of the results is influenced by the urban form and scale.
In most cases, the experiments suggest promising performance as the method tends to truthfully indicate the locations, amount, and shape of buildings.
The work has the potential to support several applications, such as energy, climate, and urban morphology studies in areas previously lacking required data or inpainting geospatial data in regions with incomplete data.
