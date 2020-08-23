---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "New graduation projects completed at our Lab"
subtitle: "Great job people, it was nice working with you"
summary: ""
authors: [admin]
tags: [teaching, theses]
categories: []
date: 2020-08-23T11:15:02+08:00
lastmod: 2020-08-23T11:15:02+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by [Damiano Lingauri](https://unsplash.com/@dendrolago89) on [Unsplash](https://unsplash.com/)."
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

We are proud to announce that in the last month, four students have completed their studies by carrying out a graduation project with us.

### Using 3D city models to uncover urban farming potential in public housing blocks of Singapore

In his thesis, {{% mention "ankit" %}} has worked on establishing a new application of [3D city models]({{< relref "../2019-08-hdb-3d/index.md" >}}): identification of locations in buildings that are suitable for urban farming.
This multidisciplinary work has been conducted in collaboration with the [NUS Department of Biological Sciences](http://www.dbs.nus.edu.sg).
His thesis has been condensed into a paper -- its preprint is available on [arXiv](https://arxiv.org/abs/2007.14203).
The work largely relies on OpenStreetMap and open-source tools, so it can be replicated elsewhere.

{{< figure library="true" src="facadesDLI.png" title="Solar exposure of building facades of a public housing block, done using 3D building models in the study area. These results are a critical insight for decision-making for high-rise urban farming and for maximizing the crop yield. To learn more, read the [preprint](https://arxiv.org/abs/2007.14203)." >}}

### Assessing the quality of OpenStreetMap building data in Singapore

As the project above suggests, building data in OpenStreetMap can be very useful.
But how good is the quality of this dataset in Singapore?
Surprisingly, this topic hasn’t been investigated much until {{% mention "ethan" %}} picked it as his graduation project.

The key result is that virtually all public housing buildings in Singapore are mapped in OpenStreetMap.
There are many aspects that the research looked into, e.g. quality of the polygons, attributes, and relation of the assessed quality to demographics in a particular area to explain the variations.
To the extent of our knowledge, this is the first study on quality of OpenStreetMap in Singapore. 
To learn more about Ethan's work, check out his [report]({{< ref "/post/2020-08-osm-singapore-building-data-quality/index.md" >}}).

{{< figure library="true" src="mean_distance.jpg" title="Mean offset distance of OSM building data and the reference dataset by cells." >}}

### Enhanced population estimation beyond counts: exploring age patterns

{{% mention "noee" %}} studies GIS at the University of Edinburgh.
This semester she has been a visiting scholar at the [NUS Urban Analytics Lab](/), carrying out a research on extending traditional population estimation methods by including the prediction of demographic data such as age.
Her research revealed that it is possible to enhance population predictions beyond traditional counts, thanks to drivers such as the density of particular amenities and the age of buildings.

{{< figure library="true" src="student-care-facilities.png" title="Locations of student care facilities in Singapore, one of the indicators of age, which was used in Noée's research." >}}

### Height inference for all US building footprints in the absence of height data

[Imke Lánský](https://nl.linkedin.com/in/imkelansky) graduated with an MSc in Geomatics at the Delft University of Technology.
We had a role in her graduation research, as it is closely related to our main project [Large-scale 3D geospatial data for urban analytics]({{< ref "/project/3d-open/index.md" >}}).

She has done a great job in developing a method to predict the heights of all buildings in the United States from various indicators such as the urban morphology.
The full-text of her thesis is available at the [TU Delft repository](https://repository.tudelft.nl/islandora/object/uuid:ddcae7d1-6cc8-42a7-8c1d-a922ec7551f0?collection=education), together with the well-documented [code](https://github.com/ImkeLansky/USA-BuildingHeightInference) (Imke, kudos for making your research reproducible :thumbsup:).

{{< figure library="true" src="height-predictions.png" title="Maps showing a comparison between building heights in the reference model and the building height predictions using three machine learning models for the CBD of Seattle, Washington. Imke's thesis is full of nice visuals, so feel free to check [it out](https://repository.tudelft.nl/islandora/object/uuid:ddcae7d1-6cc8-42a7-8c1d-a922ec7551f0?collection=education) (open access)." >}}

Congratulations to everyone on the awesome job and your degrees :mortar_board: :clap:.
We wish you all the best in your future career steps.

----------------

### Looking for a thesis topic?

Are you an NUS student and would like to carry out a cool research as your graduation project?
As it was the case last year, in the new academic year we will be accepting a few motivated students to carry out a research project with us.
Feel free to check the [topics we offer]({{< ref "/teaching/index.md#theses-and-dissertations" >}}), or you can propose your own idea.
We are also running a large [project]({{< ref "/project/3d-open/index.md" >}}) in which we have prospects for graduation research.

### Looking rather for a student researcher job?

We have announced an [opening]({{< ref "/openings/ads/2020-student-researcher-gis/index.md" >}}) for a student researcher to assist us in our projects.

