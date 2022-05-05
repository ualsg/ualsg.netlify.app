+++

widget = "blank"
headless = false  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
title= "Data and code"

subtitle = "Open resources from our group"
summary = "Open stuff"


[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"
+++ 

We believe in open science and reproducible research.
Besides open access [publications](/publication), we are committed to publishing our code and data on [our Github account](https://github.com/ualsg).

Please see below for a list of resources and projects, especially lab-grown datasets that we released openly. 

If you use the code and/or the data for presentations and publications, we kindly ask you to cite the related paper(s) and credit our work. 
We have provided guidelines to do so in each resource.

While a great deal of effort has been put into each project, they are not free of errors, and we cannot be held responsible for the use of data and any issues that may arise.

Feel free to contact us for more information, report bugs and errors, or simply to inform us what are you using the data for.
We would be pleased to hear how others are using our research.
In you are interested in collaborating with us, please check the opportunities tab for more information or get in touch with the lead developer of each resource.

## GBMI -- Global Building Morphology Indicators

![GBMI London](gbmi-london.png)

| | |
| ------------------| ------------------------------ |
| Short description: | Billions of built form metrics of selected urban areas around the world, together with a database solution to compute them |
| Lead developer: | {{% mention "yoong-shin" %}} |
| Formats | CSV, Shapefile, Geopackage, GeoTIFF |
| Further reading: | Please read more at our [website]({{< ref "/project/gbmi/index.md" >}}) or in the [paper](https://doi.org/10.1016/j.compenvurbsys.2022.101809) |
| Download: | [Project website](/project/gbmi/) |
| Code: | The code used to generate the dataset is available in the [<i class="fab fa-github"></i>  Github repo](https://github.com/ualsg/global-building-morphology-indicators) |
| Main data source(s): | OpenStreetMap, GADM |
| Coverage: | Dozens of urban areas around the world | 
| Citation: | {{< spoiler text="Click to view the BibTeX entry" >}}
@article{2022_ceus_gbmi,
 author = {Biljecki, Filip and Chow, Yoong Shin},
 doi = {10.1016/j.compenvurbsys.2022.101809},
 journal = {Computers, Environment and Urban Systems},
 pages = {101809},
 title = {Global Building Morphology Indicators},
 volume = {95},
 year = {2022}
}
{{< /spoiler >}}|


## Roofpedia -- solar and green roofs around the world

![Density of solar panels in Singapore](roofpedia-singapore.png)

| | |
| ------------------| ------------------------------ |
| Short description: | Locations of buildings that have installed photovoltaics or greenery on their rooftops |
| Lead developer: | {{% mention "abraham" %}} |
| Formats | GeoJSON |
| Further reading: | Please read more at our [website]({{< ref "/project/roofpedia/index.md" >}}) or in the [paper](https://doi.org/10.1016/j.landurbplan.2021.104167) |
| Download: | [<i class="fab fa-github"></i> Github repo](https://github.com/ualsg/Roofpedia) |
| Code: | The code used to generate the dataset is available in the [same <i class="fab fa-github"></i>  Github repo](https://github.com/ualsg/Roofpedia) |
| Main data source(s): | Various satellite imagery, OpenStreetMap. All open data |
| Coverage: | 17 cities around the world | 
| Citation: | {{< spoiler text="Click to view the BibTeX entry" >}}
@article{roofpedia,
  author = {Abraham Noah Wu and Filip Biljecki},
  doi = {10.1016/j.landurbplan.2021.104167},
  journal = {Landscape and Urban Planning},
  pages = {104167},
  title = {Roofpedia: Automatic mapping of green and solar roofs for an open roofscape registry and evaluation of urban sustainability},
  url = {https://doi.org/10.1016/j.landurbplan.2021.104167},
  volume = {214},
  year = 2021
}
{{< /spoiler >}}|

## Semantic Riverscapes

![A section of the Grand Canal in Tianjin](semantic-riverscapes.jpg)

| | |
| ------------------| ------------------------------ |
| Short description: | A semantically annotated UAV oblique image dataset covering an urban river landscape |
| Lead developer: | {{% mention "junjie" %}} |
| Further reading: | Paper in progress... Stay tuned |
| Download: | [<i class="fab fa-github"></i> Github repo](https://github.com/ualsg/semantic-riverscapes-dataset) |
| Main data source(s): | Own data collection (UAV) and manual labelling |
| Coverage: | Tianjin (China) | 


## Classification of Urban Morphology with Deep Learning

![](urban-morphology-classification.jpg)

| | |
| ------------------| ------------------------------ |
| Short description: | Software to generate diagrams of the urban form at the city-scale and classify them using deep learning |
| Lead developer: | {{% mention "wangyang" %}} |
| Further reading: | Please read more in the [paper](https://doi.org/10.1016/j.compenvurbsys.2021.101706) |
| Code: | [<i class="fab fa-github"></i> Github repo](https://github.com/ualsg/Road-Network-Classification) |
| Citation: | {{< spoiler text="Click to view the BibTeX entry" >}}
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
{{< /spoiler >}}|

## GANmapper: geographical content translation

![](ganmapper.jpg)

| | |
| ------------------| ------------------------------ |
| Short description: | A building footprint generator using Generative Adversarial Networks from sparse data such as street networks |
| Lead developer: | {{% mention "abraham" %}} |
| Further reading: | Please read more in the [IJGIS paper](https://doi.org/10.1080/13658816.2022.2041643) |
| Code: | [<i class="fab fa-github"></i> Github repo](https://github.com/ualsg/GANmapper) |
| Citation: | {{< spoiler text="Click to view the BibTeX entry" >}}
@article{2022_ijgis_ganmapper, 
  year = {2022}, 
  author = {Wu, Abraham Noah and Biljecki, Filip}, 
  title = {{GANmapper: geographical data translation}}, 
  journal = {International Journal of Geographical Information Science}, 
  doi = {10.1080/13658816.2022.2041643}
}
{{< /spoiler >}}|

## 3D dataset of all public housing (HDB) buildings in Singapore 

![HDB 3D city model, Singapore](hdb3d-c4_att_cut.png)

| | |
| ------------------| ------------------------------ |
| Short description: | About 12k semantically rich 3D buildings in Singapore in CityJSON and OBJ |
| Lead developer: | {{% mention "filip" %}} |
| Formats | [CityJSON](https://cityjson.org), [OBJ](https://en.wikipedia.org/wiki/Wavefront_.obj_file) |
| Further reading: | Please read more here in our [blog post]({{< ref "/post/2019-08-hdb-3d/index.md" >}}) or in the [paper](/publication/2020-3-dgeoinfo-3-d-asean/) |
| Download: | [<i class="fab fa-github"></i> Github repo](https://github.com/ualsg/hdb3d-data) |
| Code: | The code used to generate the dataset is available in a [separate <i class="fab fa-github"></i>  Github repo](https://github.com/ualsg/hdb3d-code) |
| Main data source(s): | HDB, OpenStreetMap, OneMap. All open data |
| Coverage: | Singapore | 
| Citation: | {{< spoiler text="Click to view the BibTeX entry" >}}
@article{2020_3dgeoinfo_3d_asean,
 author = {Biljecki, F.},
 doi = {10.5194/isprs-annals-vi-4-w1-2020-37-2020},
 journal = {ISPRS Annals of Photogrammetry, Remote Sensing and Spatial Information Sciences},
 pages = {37--44},
 title = {Exploration of open data in Southeast Asia to generate 3D building models},
 volume = {VI-4/W1-2020},
 year = {2020}
}
{{< /spoiler >}}|
