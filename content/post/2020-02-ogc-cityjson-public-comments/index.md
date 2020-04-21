---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "OGC considering CityJSON as community standard"
subtitle: "CityJSON provides a simplified alternative to the GML encoding of CityGML that is also lightweight and suitable for use on the web and mobile"
summary: "CityJSON provides a simplified alternative to the GML encoding of CityGML that is also lightweight and suitable for use on the web and mobile"
authors: [admin]
tags: [cityjson, ogc]
categories: []
date: 2020-02-15T19:50:15+08:00
lastmod: 2020-02-15T19:50:15+08:00
featured: false
draft: false

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
projects: []
---

We're relaying [a press release from the Open Geospatial Consortium](https://www.opengeospatial.org/pressroom/pressreleases/3152) about [CityJSON](https://cityjson.org), a standard which we endorsed as OGC member, and have been using in our work, e.g. [to produce 3D data of Singapore's public housing buildings]({{< ref "/post/2019-08-hdb-3d/index.md" >}}).

## OGC considering CityJSON as community standard; seeks public comment for new Work Item

#### Release Date: Thursday, 13 February 2020 UTC
CityJSON provides a simplified alternative to the GML encoding of CityGML that is also lightweight and suitable for use on the web and mobile.

The Open Geospatial Consortium (OGC) is considering CityJSON for adoption as an official OGC Community Standard. A new Work Item justification to begin the Community Standard endorsement process is available for public comment.

CityJSON is a JSON-based encoding for a subset of the [OGC CityGML data model](https://www.opengeospatial.org/standards/citygml), which is an open standardized data model and exchange format to store digital 3D models of cities and landscapes. 

CityJSON defines ways to describe most of the common 3D features and objects found in cities (such as buildings, roads, rivers, bridges, vegetation, and city furniture) and the relationships between them. It also defines different standard levels of detail (LoDs) for the 3D objects, which allows different resolutions of objects for different applications and purposes. CityJSON considerably simplifies the storage and exchange of 3D city models.

The purpose of CityJSON is to offer an alternative to the GML encoding of CityGML, which can be verbose and therefore complex to work with. The design objective for CityJSON is ease of use for both reading datasets and for creating them. CityJSON was designed with programmers in mind, therefore tools and APIs supporting it can be quickly built. It was also designed to be compact - using CityJSON typically compresses publicly available CityGML files by a factor of 6x - while at the same time being friendly for web and mobile development.

CityJSON was developed, and is maintained, by the [3D geoinformation group at TU Delft](https://3d.bk.tudelft.nl/). Others have since joined its development, especially [virtualcitySYSTEMS](https://www.virtualcitysystems.de/) and Claus Nagel.

An approved [OGC Community Standard](http://www.opengeospatial.org/blog/2543) is an official standard of OGC that is considered to be a widely used, mature specification, but was developed outside of OGC’s standards development and approval process. The originator of the standard brings to OGC a “snapshot” of their work that is then endorsed by OGC membership so that it can become part of the OGC Standards Baseline. 

The proposed CityJSON community standard work item justification is available for review and comment on the [OGC Portal](https://portal.opengeospatial.org/files/91843). Comments are due by 5th March, 2020, and should be submitted via the method outlined on the [CityJSON community standard work item public comment request page](https://www.opengeospatial.org/standards/requests/200).

### About OGC

The Open Geospatial Consortium (OGC) is an international consortium of more than 530 businesses, government agencies, research organizations, and universities driven to make geospatial (location) information and services FAIR - Findable, Accessible, Interoperable, and Reusable.
OGC’s member-driven consensus process creates royalty free, publicly available geospatial standards. Existing at the cutting edge, OGC actively analyzes and anticipates emerging tech trends, and runs an agile, collaborative Research and Development (R&D) lab that builds and tests innovative prototype solutions to members' use cases.
OGC members together form a global forum of experts and communities that use location to connect people with technology and improve decision-making at all levels. OGC is committed to creating a sustainable future for us, our children, and future generations.
Visit [ogc.org](http://ogc.org/) for more info on our work.

#### Contact: info@opengeospatial.org

