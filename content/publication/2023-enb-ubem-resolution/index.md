---
# Documentation: https://wowchemy.com/docs/managing-content/

title: How spatio-temporal resolution impacts urban energy calibration
subtitle: ''
summary: ''
authors:
- Aysegul Demir Dilsiz
- Kingsley E. Nweye
- Allen J. Wu
- Jérôme H. Kämpf
- filip
- Zoltan Nagy
tags: []
categories: []
date: '2023-05-26'
lastmod: 2023-05-26T08:07:59+08:00
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
publishDate: '2023-05-26T00:07:58.824379Z'
publication_types:
- '2'
abstract: 'Building Energy Modeling tools help forecast the energy performance of buildings. Urban energy models (UBEMs) emerged as important instruments to analyze the energy performance of buildings aggregated at different spatial resolutions, from the building level to the district level. They heavily rely on available data on geometries and measurements to create accurately calibrated energy models. However, limited research has been conducted to understand the impact of spatial and temporal resolution on the simulation results because of the difficulty of comparing results and not having a standardized procedure to report simulation errors. We review the literature on UBEM validation compared to measured energy data and show the discrepancies in the reporting accuracy. We articulate the need for consistent reporting on model accuracy and introduce a multi-dimensional Level of Detail (LoD) specification for UBEM, including geometry, thermal zoning, and spatio-temporal resolution of the measured data used to calibrate the models. Using a university campus with 70 buildings as an extensive case study, we demonstrate the performance of Bayesian calibration from the building level to the aggregated level. Our results suggest that the accuracy of urban energy prediction with annual temporal resolution can be significantly increased if calibration is performed by using building-level data. However, whenever privacy is a concern, then the data should be provided by aggregating them based on primary use type. Additionally, using monthly data to calibrate uncertain input parameters is not improving the accuracy of the models because the obtained posterior distributions for the selected parameters are not informative for monthly data. To improve this shortcoming, we suggest seasonal calibration, which is computationally costly.'
publication: '*Energy and Buildings*'
doi: 10.1016/j.enbuild.2023.113175
---
