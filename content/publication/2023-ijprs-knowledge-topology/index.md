---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Knowledge and topology: A two layer spatially dependent graph neural networks
  to identify urban functions with time-series street view image'
subtitle: ''
summary: ''
authors:
- yan-zhang
- pengyuan
- filip
tags: []
categories: []
date: '2023-03-16'
lastmod: 2023-03-17T08:40:37+08:00
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
publishDate: '2023-03-17T00:40:37.215854Z'
publication_types: ['article-journal']
abstract: 'With the rise of GeoAI research, streetscape imagery has received extensive attention due to its comprehensive coverage, abundant information, and accessibility. However, obtaining a holistic spatial–temporal scene representation is difficult because places are often composed of multiple images from different angles, times and locations. This problem also exists in other types of geo-tagged imagery. To solve it, we propose a purely visual, robust, and reliable method for urban function identification at the street scale. We introduce a method based on a two-layer spatially dependent graph neural network structure, which handles sequential street view imagery as input (typically available in services such as Google Street View, Baidu Maps, and Mapillary), with full consideration of the spatial dependencies among road networks. In this paper, we construct an urban topological map network using OpenStreetMap data in Wuhan, China, and compute a semantic representation of the scene as a whole at the street scale using a large-scale pre-trained model. We construct the graph network with streets as nodes based on 28,693 mapping relationships constructed from 75,628 street view images and 5,458 streets. Only 5.3% of the node labels were required to obtain 10 categories of functions for all nodes in the study area. The results demonstrate that by using appropriate spatial weights, street encoder, and graph structure, our novel method achieves high accuracy of P@1 46.2%, P@3 73.0%, P@5 82.4%, and P@10 89.9%, fully demonstrating the effectiveness of the introduced approach. We also use the model to sense urban spatial–temporal renewal by computing time series street images. The model is also applicable to the prediction of other attributes, where only a small number of labels are required to obtain valid and reliable scene perception results. The example data and code is shared at: https://github.com/yemanzhongting/Knowledge-and-Topology.'
publication: '*ISPRS Journal of Photogrammetry and Remote Sensing*'
doi: 10.1016/j.isprsjprs.2023.03.008
---
