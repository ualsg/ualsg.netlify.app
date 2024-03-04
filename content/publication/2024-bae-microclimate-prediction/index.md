---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Microclimate spatio-temporal prediction using deep learning and land use data
subtitle: ''
summary: ''
authors:
- jintong
- Adrian Chong
- Joie Lim
- Savitha Ramasamy
- Nyuk Hien Wong
- filip
tags: []
categories: []
date: '2024-02-29'
lastmod: 2024-03-04T10:28:41+08:00
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
publishDate: '2024-03-04T02:28:17.578694Z'
publication_types:
- '2'
abstract: 'Urban microclimate prediction is crucial for various fields, including Building Performance Simulation (BPS), outdoor thermal comfort, building life cycle, and residential health. Existing methods involve using classical weather file data, such as Typical Meteorological Years (TMY), or machine learning techniques for time-based forecasting. However, the incorporation of both spatial and temporal dimensions and land use/land cover (LULC) data is seldom considered. This paper proposes a novel approach to predict microclimate: the Geo-LSTM-Kriging model, which is applicable for fine-scale microclimate prediction within a few hundred meters around weather stations. The Geo-layer processes and learns from LULC data, the LSTM layer learns from historical data, and the Kriging layer extracts spatial distance information. This comprehensive combination integrates spatial, temporal, and environmental conditions, providing accurate results with higher spatial resolution (1 m x 1 m) and shorter time intervals (10 min). These prediction results were achieved by employing statistical downscaling calculation and utilizing data from 14 weather stations located within our university campus. Upon the analysis of these prediction results, we found that the proposed model can accurately predict temperature and humidity at high spatial and temporal resolution. Compared to traditional interpolation models, the RMSE of temperature decreases from 1.59 °C to 0.64 °C, and the RMSE of relative humidity (RH) decreases from 7.70 to 3.23. A thorough analysis of the model prediction results reveals the varied impacts of different LULC features on microclimate predictions, highlighting the value of the proposed model and the importance of incorporating LULC data.'
publication: '*Building and Environment*'
doi: 10.1016/j.buildenv.2024.111358
---
