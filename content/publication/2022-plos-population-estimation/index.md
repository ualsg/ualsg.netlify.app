---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Population estimation beyond counts---Inferring demographic characteristics
subtitle: ''
summary: ''
authors:
- Noée Szarka
- filip
tags: []
categories: []
date: '2022-04-06'
lastmod: 2022-04-06T19:52:07+08:00
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
publishDate: '2022-04-06T11:52:06.697814Z'
publication_types:
- '2'
abstract: ''
publication: '*PLOS ONE*'
doi: 10.1371/journal.pone.0266484
---

Mapping population distribution at a fine spatial scale is essential for urban studies and planning. Numerous studies, mainly supported by geospatial and statistical methods, have focused primarily on predicting population counts. However, estimating their socio-economic characteristics beyond population counts, such as average age, income, and gender ratio, remains unattended. We enhance traditional population estimation by predicting not only the number of residents in an area, but also their demographic characteristics: average age and the proportion of seniors. By implementing and comparing different machine learning techniques (Random Forest, Support Vector Machines, and Linear Regression) in administrative areas in Singapore, we investigate the use of point of interest (POI) and real estate data for this purpose. The developed regression model predicts the average age of residents in a neighbourhood with a mean error of about 1.5 years (the range of average resident age across Singaporean districts spans approx. 14 years). The results reveal that age patterns of residents can be predicted using real estate information rather than with amenities, which is in contrast to estimating population counts. Another contribution of our work in population estimation is the use of previously unexploited POI and real estate datasets for it, such as property transactions, year of construction, and flat types (number of rooms). Advancing the domain of population estimation, this study reveals the prospects of a small set of detailed and strong predictors that might have the potential of estimating other demographic characteristics such as income.