---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "New paper: Classification of Urban Morphology with Deep Learning"
subtitle: "A leading journal -- Computers, Environment and Urban Systems, publishes our pioneering work on the application of computer vision in studying the urban form"
summary: "A leading journal -- Computers, Environment and Urban Systems, publishes our pioneering work on the application of computer vision in studying the urban form"
authors: [admin]
tags: [paper, urban morphology, deep learning, computer vision, thesis, dissertation]
categories: []
date: 2021-08-22T09:55:16+08:00
lastmod: 2021-08-22T09:55:16+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Categorical maps of cities derived from our automatic classification method."
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.

---

We have a new paper:

> Chen W, Wu AN, Biljecki F (2021): Classification of Urban Morphology with Deep Learning: Application on Urban Vitality. _Computers, Environment and Urban Systems_ 90: 101706. [<i class="ai ai-doi-square ai"></i> 10.1016/j.compenvurbsys.2021.101706](https://doi.org/10.1016/j.compenvurbsys.2021.101706) [<i class="far fa-file-pdf"></i> PDF](/publication/2021-ceus-dl-morphology/2021-ceus-dl-morphology.pdf)</i>


In this research, an entirely new approach to characterise the urban form is developed.
The resulting data, derived at a high resolution (the example of the classification is available in the header image above), is then used to study its association with vibrancy in 9 cities.

Congratulations to {{% mention "wangyang" %}}, our Master of Urban Planning graduate, on the great job and his first paper! :raised_hands: :clap:

The code supporting this research has been [released as open-source software](https://github.com/ualsg/Road-Network-Classification). 

CEUS is a top 1% journal in its discipline according to Scopus.


### Highlights

- Characterizing urban morphology is important in urban analytics
- The use of deep learning has not been investigated for this purpose
- We develop an approach to automatically classify urban forms from street networks
- The value of the work is demonstrated on an application on urban vitality
- Our deep learning approach reveals additional insights and enhances studies


### Abstract

The abstract follows.

> There is a prevailing trend to study urban morphology quantitatively thanks to the growing accessibility to various forms of spatial big data, increasing computing power, and use cases benefiting from such information. The methods developed up to now measure urban morphology with numerical indices describing density, proportion, and mixture, but they do not directly represent morphological features from the human's visual and intuitive perspective. We take the first step to bridge the gap by proposing a deep learning-based technique to automatically classify road networks into four classes on a visual basis. The method is implemented by generating an image of the street network (Colored Road Hierarchy Diagram), which we introduce in this paper, and classifying it using a deep convolutional neural network (ResNet-34). The model achieves an overall classification accuracy of 0.875. Nine cities around the world are selected as the study areas with their road networks acquired from OpenStreetMap. Latent subgroups among the cities are uncovered through clustering on the percentage of each road network category. In the subsequent part of the paper, we focus on the usability of such classification: we apply our method in a case study of urban vitality prediction. An advanced tree-based regression model (LightGBM) is for the first time designated to establish the relationship between morphological indices and vitality indicators. The effect of road network classification is found to be small but positively associated with urban vitality. This work expands the toolkit of quantitative urban morphology study with new techniques, supporting further studies in the future.

### Paper 

For more information, please see the [paper](/publication/2021-ceus-dl-morphology/).

[![](page-one.png)](/publication/2021-ceus-dl-morphology/)

BibTeX citation:
```bibtex
@article{2021_ceus_dl_morphology,
  author = {Wangyang Chen and Abraham Noah Wu and Filip Biljecki},
  doi = {10.1016/j.compenvurbsys.2021.101706},
  journal = {Computers, Environment and Urban Systems},
  pages = {101706},
  title = {Classification of Urban Morphology with Deep Learning: Application on Urban Vitality},
  url = {https://doi.org/10.1016/j.compenvurbsys.2021.101706},
  volume = {90},
  year = 2021
}
```


