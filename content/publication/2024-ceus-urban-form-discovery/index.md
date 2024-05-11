---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning visual features from figure-ground maps for urban morphology discovery
subtitle: ''
summary: ''
authors:
- wang-jing
- Weiming Huang
- filip
tags: []
categories: []
date: '2024-02-04'
lastmod: 2024-02-04T19:58:56+08:00
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
publishDate: '2024-02-04T11:58:13.006473Z'
publication_types: ['article-journal']
abstract: 'Most studies of urban morphology rely on morphometrics, such as building area and street length. However, these methods often fall short in capturing visual patterns that carry abundant information about the configuration of urban elements and how they interact spatially. In this study, we introduce a novel method for learning morphology features based on figure-ground maps, which leverages recent developments in computer vision. Our method facilitates discovering and comparing urban form types in a fully unsupervised manner. Specifically, we examine building fabrics by 1 km patches. A visual representation learning model (SimCLR) casts each patch into a latent embedding space where similar patches are clustered while dissimilar patches are dispelled, thus generating morphology representations that entail the layout of building groups. The learned morphology features are tested in urban form typology clustering and comparison tasks in four diverse cities: Singapore, San Francisco, Barcelona, and Amsterdam, with data sourced from OpenStreetMap. Clustering results show effective identification of typical urban morphology types corresponding to urban functions and historical developments. Further analyses based on the representations reveal inner- and cross-city morphological homogeneity relating to socio-economic drivers. We conclude that this method is a promising alternative for effectively describing urban patterns in morphology analysis.'
publication: '*Computers, Environment and Urban Systems*'
doi: 10.1016/j.compenvurbsys.2024.102076
---
