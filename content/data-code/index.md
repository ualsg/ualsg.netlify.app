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

We publish most of our code and data on [our Github account](https://github.com/ualsg).

Please see below for a list of resources and projects, especially lab-grown datasets that we released openly. 
On this page, we also include [outputs led by collaborators](#with-our-friendly-collaborators), in which we were involved.

On a related note, you may be interested in [our comprehensive survey on open-source software](https://doi.org/10.1016/j.compenvurbsys.2022.101825), published as a review paper in CEUS.

In general, all code and data are released under a liberal licence, enabling you unrestricted use as long as you attribute them.
If you use the code and/or the data for presentations and publications, we kindly ask you to cite the related paper(s) and credit our work. 
We have provided guidelines to do so in each resource.

While a great deal of effort has been put into each project, they are not free of errors, and we cannot be held responsible for the use of code and/or data and any issues that may arise.

Feel free to contact us for more information, report bugs and errors, or simply to inform us what are you using the data for.
We would be pleased to hear how others are using our research.
In you are interested in collaborating with us, please get in touch with the lead developer of each resource.

## Water View Imagery

![](water-view-imagery.png)

| | |
| ------------------| ------------------------------ |
| Short description: | On-water perspective imagery dataset for semantic segmentation of waterscapes. |
| Lead developer: | {{% mention "junjie" %}} |
| Further reading: | Paper in progress... Stay tuned |
| Download: | [<i class="fab fa-github"></i> Github repo](https://github.com/ualsg/Water-View-Imagery-dataset) |
| Main data source(s): | Mapillary and manual labelling |
| Coverage: | Eight cities: Amsterdam, Bangkok, Chicago, Istanbul, Japan, London, Paris, and Venice | 

## Global Urban Road Network Patterns

![](gurnp.png)

| | |
| ------------------| ------------------------------ |
| Short description: | Deep learning-based analysis of the urban morphology around the world |
| Lead developer: | {{% mention "wangyang" %}} |
| Further reading: | Readme on the Github repo. Paper in progress, stay tuned |
| Code: | [<i class="fab fa-github"></i>  Github repo](https://github.com/ualsg/Global-road-network-patterns) |
| Main data source(s): | OpenStreetMap |

## SVIQC -- Street View Imagery Quality Checker

![](kowloon-grid.png)

| | |
| ------------------| ------------------------------ |
| Short description: | A toolkit to examine the quality of street view imagery |
| Lead developer: | {{% mention "yujun" %}} |
| Further reading: | Readme on the Github repo. Paper in progress, stay tuned |
| Code: | [<i class="fab fa-github"></i>  Github repo](https://github.com/ualsg/SVI-Quality-Checker) |
| Main data source(s): | Mapillary |

## Visual soundscapes

![](visual-soundcapes.png)

| | |
| ------------------| ------------------------------ |
| Short description: | Predicting the urban soundscape from street view imagery |
| Lead developer: | {{% mention "tianhong" %}} |
| Further reading: | Readme on the Github repo. Paper in progress, stay tuned |
| Code: | [<i class="fab fa-github"></i>  Github repo](https://github.com/ualsg/Visual-soundscapes) |

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


# With our friendly collaborators

## EUropean BUilding stock Characteristics in a Common and Open database

![](eubucco.png)

| | |
| ------------------| ------------------------------ |
| Short description: | EUBUCCO is a scientific database of individual building footprints for 206 million buildings across the 27 European Union countries and Switzerland, together with three main attributes -- building type, height and construction year -- included for respectively 45%, 74%, 24% of the buildings. |
| Lead developer: | [Nikola Milojevic-Dupont](https://milojevicdupontnikola.github.io) and [Felix Wagner](https://www.susturbecon.tu-berlin.de/team/felix_wagner/), [3D Geoinformation](https://3d.bk.tudelft.nl), [Mercator Research Institute for Global Commons and Climate Change](https://www.mcc-berlin.net/) and TU Berlin |
| Code: | [<i class="fab fa-github"></i> Github repo](https://github.com/ai4up/eubucco) |
| Data: | [Zenodo](https://zenodo.org/record/6524781#.YnzjZ1xBygo) |

## 3D building metrics for urban morphology

![](3dbm.png)

| | |
| ------------------| ------------------------------ |
| Short description: | 3D Building Metrics. Elevating geometric analysis for urban morphology, solar potential, CFD etc to the next level |
| Lead developers: | [Anna Labetski](http://3d.bk.tudelft.nl/alabetski) and [Stelios Vitalis](http://3d.bk.tudelft.nl/svitalis), [3D Geoinformation](https://3d.bk.tudelft.nl), TU Delft |
| Code: | [<i class="fab fa-github"></i> Github repo](https://github.com/tudelft3d/3d-building-metrics) |
| Data: | [Repository](https://doi.org/10.7910/DVN/6QCRRF) |
| Further reading: | Please read the [paper](https://doi.org/10.1080/13658816.2022.2103818) |
| Coverage: | Major cities in the Netherlands, extensible thanks to the code released open-source | 
| Citation: | {{< spoiler text="Click to view the BibTeX entry" >}}
@article{2022_ijgis_3dbm,
  author = {Labetski, Anna and Vitalis, Stelios and Biljecki, Filip and Arroyo Ohori, Ken and Stoter, Jantien},
  journal = {International Journal of Geographical Information Science},
  title = {3D building metrics for urban morphology},
  year = {2022},
  doi = {10.1080/13658816.2022.2103818}
}
{{< /spoiler >}}|




## 3dfier: automatic reconstruction of 3D city models

![](3dfier.jpg)

| | |
| ------------------| ------------------------------ |
| Short description: | Takes 2D GIS datasets (e.g. topographical datasets) and "3dfies" them (as in "making them three-dimensional") by lifting every polygon to 3D |
| Lead developer: | [3D Geoinformation](https://3d.bk.tudelft.nl), TU Delft |
| Code: | [<i class="fab fa-github"></i> Github repo](https://github.com/tudelft3d/3dfier) |
| Further reading: | Please read more in the [paper](https://doi.org/10.21105/joss.02866) |
| Citation: | {{< spoiler text="Click to view the BibTeX entry" >}}
@article{2021_joss_3dfier,
 author = {Ledoux, Hugo and Biljecki, Filip and Dukai, Balázs and Kumar, Kavisha and Peters, Ravi and Stoter, Jantien and Commandeur, Tom},
 doi = {10.21105/joss.02866},
 journal = {Journal of Open Source Software},
 number = {57},
 pages = {2866},
 title = {3dfier: automatic reconstruction of 3D city models},
 volume = {6},
 year = {2021}
}
{{< /spoiler >}}|

## ifc2indoorgml

![](ifc2indoorgml.png)

| | |
| ------------------| ------------------------------ |
| Short description: | A tool allowing to generate IndoorGML files from IFC input models |
| Lead developer: | [Abdoulaye Diakite](https://www.unsw.edu.au/staff/abdoulaye-diakite), [GRID](http://grid.unsw.edu.au/), University of New South Wales |
| Code: | [<i class="fab fa-github"></i> Github repo](https://github.com/grid-unsw/ifc2indoorgml) |
| Further reading: | [Paper](/publication/2022-isprs-ifc-2-indoorgml/) |
| Citation: | {{< spoiler text="Click to view the BibTeX entry" >}}
@article{2022_isprs_ifc2indoorgml,
 author = {Diakite, AA and Díaz-Vilariño, L and Biljecki, F and Isikdag, Ü and Simmons, S and Li, K and Zlatanova, S},
 doi = {10.5194/isprs-archives-xliii-b4-2022-295-2022},
 journal = {Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci.},
 pages = {295--301},
 title = {ifc2indoorgml: An open-source tool for generating IndoorGML from IFC},
 volume = {XLIII-B4-2022},
 year = {2022}
}
{{< /spoiler >}}|

## AIDA - Annotated Image Database of Architecture

| | |
| ------------------| ------------------------------ |
| Short description: | A repository of architectural photographs worldwide, labelled with a vast list of hierarchical categories and a series of auxiliary annotations |
| Lead developer: | Chen Jielin |
| Further reading: | [Paper](/publication/2021-caadria-aida/) |
| Download: | [Harvard Dataverse](https://doi.org/10.7910/DVN/IGNELZ) |
| Main data source(s): | ArchDaily |
| Citation: | {{< spoiler text="Click to view the BibTeX entry" >}}
@inproceedings{2021_caadria_aida,
 author = {Chen, Jielin and Stouffs, Rudi and Biljecki, Filip},
 booktitle = {Proceedings of the 26th International Conference of the Association for Computer-Aided Architectural Design Research in Asia (CAADRIA) 2021},
 pages = {161--170},
 title = {Hierarchical (Multi-Label) Architectural Image Recognition and Classification},
 volume = {1},
 year = {2021}
}
{{< /spoiler >}}|

