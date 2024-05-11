---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Assessing the quality of OpenStreetMap building data in Singapore"
subtitle: "A new study focusing on buildings"
summary: ""
authors: [ethan]
tags: [report, teaching, openstreetmap]
categories: []
date: 2020-08-22T10:15:02+08:00
lastmod: 2020-08-22T10:15:02+08:00
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
projects: [3d-open]
---

A new [report]({{< ref "/publication/2020-osm-sg-building-quality/index.md" >}}) on OpenStreetMap (OSM) data quality assessment in Singapore has been published.
The report describes a recent research project carried at the Lab by {{% mention "ethan" %}}, focusing on residential buildings.
Its summary follows.

As OpenStreetMap is getting increasingly popular due to its open-license nature and collaborative aspect, its data quality is increasingly under scrutiny from many geospatial enthusiasts and scientists.
Given that many web services and scientific researchers are relying on OpenStreetMap data as the primary data source, data inaccuracy would cause unforeseen problems.
Therefore, it is imperative to assess the quality of OpenStreetMap data in order to identify areas of improvement and to improve the reliability of OpenStreetMap data.
While the assessment of OpenStreetMap data quality is an ongoing task in many countries, there is a lack of such assessments in Singapore.
Therefore, this study was conducted to address this research gap.

Five quality metrics of Housing & Development Board (HDB) buildings were studied and analysed as part of the assessment of OpenStreetMap building data quality in Singapore: completeness, positional accuracy, shape accuracy, orientation accuracy, and attribute accuracy.
The results of this study suggest that the completeness of HDB building data in Singapore is close to perfect, with 97.67% of the HDB blocks being mapped in OpenStreetMap.

Taking all quality metrics into account, it was concluded from this study that the overall quality of HDB buildings in Singapore is fairly good, with some room for improvement.
With regard to improving the overall quality of OpenStreetMap data, this study recommends that the OpenStreetMap community explores building a data quality warning system for its users.
In addition, correlation analyses revealed that both the median age of planning areas and the mean age of HDB buildings have weak relationships with the data quality of HDB buildings in Singapore.
Furthermore, this study has also found that it is currently not feasible to use attributes of HDB buildings in OpenStreetMap to build [semantically rich 3D building models]({{< ref "/post/2019-08-hdb-3d/index.md" >}}), as these attributes are mostly unfilled.

The full report is available [here]({{< ref "/publication/2020-osm-sg-building-quality/index.md" >}}).
This research has been conducted by {{% mention "ethan" %}} as part of the GE6226 GIS Research Project module of MSc in Applied GIS programme in NUS.

