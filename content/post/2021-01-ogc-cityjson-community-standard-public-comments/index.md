---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "OGC seeks public comment on new CityJSON Community Standard"
subtitle: "CityJSON offers an easy-to-use alternative to the GML encoding of CityGML 2.0 for the storage and exchange of 3D city models"
summary: "CityJSON offers an easy-to-use alternative to the GML encoding of CityGML 2.0 for the storage and exchange of 3D city models"
authors: [admin]
tags: [cityjson, ogc, 3d, 3d city models]
categories: []
date: 2021-01-09T10:04:15+08:00
lastmod: 2021-01-09T10:04:15+08:00
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
projects: []
---

We're relaying [a press release by the Open Geospatial Consortium](https://www.ogc.org/pressroom/pressreleases/4381) about [CityJSON](https://cityjson.org), which we have (on behalf of the National University of Singapore as OGC member) submitted to OGC for adoption as a [Community Standard](https://www.ogc.org/standards/community) together with 6 other organisations (full list below), and have been using in our work, e.g. [to produce 3D data of Singapore's public housing buildings]({{< ref "/post/2019-08-hdb-3d/index.md" >}}).

## OGC seeks public comment on new CityJSON Community Standard

#### Release Date: 7 January 2021
The Open Geospatial Consortium (OGC) seeks public comment on its adoption of CityJSON as an [OGC Community Standard](https://www.ogc.org/standards/community).

CityJSON is a [JSON](https://json.org/)-based encoding for a subset of the [OGC CityGML data model](http://www.ogc.org/standards/citygml) (version 2.0.0). CityJSON defines ways to describe most of the common 3D features and objects found in cities (such as buildings, roads, rivers, bridges, vegetation, and city furniture) and the relationships between them. It also defines different standard levels of detail (LoDs) for the 3D objects, which allows different resolutions of objects for different applications and purposes.

A CityJSON file describes both the geometry (an object’s form) and the semantics (an object’s function) of the features in a given area, such as the buildings, roads, rivers, vegetation, and city furniture.

The aim of CityJSON is to offer an alternative to the GML encoding of CityGML, which can be verbose and complex to read and manipulate. CityJSON aims at being easy-to-use, both for reading datasets and for creating them. It was designed with programmers in mind, so that tools and APIs supporting it can be quickly built.

The differences between the CityJSON v1.0 implementation and the XML-based implementation are described in more detail on [this webpage](https://www.cityjson.org/citygml-compatibility).

Please note that the [CityGML 3.0 Conceptual Model specification is also currently open for public comments](https://www.ogc.org/pressroom/pressreleases/4370). CityGML 3.0 is a data model that has been re-structured to be independent of particular encodings; it may have a JSON encoding in the future. CityJSON 1.0 provides a directly implementable JSON encoding based on the CityGML 2.0 data model, an OGC standard since 2012. GML encodings and JSON encodings address different use cases – different communities looking to achieve different things, each useful in their own right. Hence, the OGC community sees value in offering both CityGML 3.0 and CityJSON 1.0.

CityJSON has been submitted to OGC for adoption as a Community Standard by the following organizations: Geonovum, Delft University of Technology, Kadaster International, virtualcitySYSTEMS, National University of Singapore, Forum Virium Helsinki Oy, and Ordnance Survey.

An OGC Community Standard is an official Standard of OGC that is considered to be a widely used, mature specification, but was developed outside of OGC’s standards development process. The originator of the standard brings to OGC a “snapshot” of their work that is then endorsed by OGC membership so that it can become part of the OGC Standards Baseline. 

_The candidate [CityJSON Community Standard 1.0](https://portal.ogc.org/files/?artifact_id=95618&version=1) is available for review and comment on the [OGC Portal](https://portal.ogc.org/files/?artifact_id=95618&version=1). Comments are due by February 7, 2021, and should be submitted via the method outlined on the [CityJSON Community Standard 1.0’s public comment request page](https://www.ogc.org/standards/requests/222)._



### About OGC

The Open Geospatial Consortium (OGC) is an international consortium of more than 500 businesses, government agencies, research organizations, and universities driven to make geospatial (location) information and services FAIR - Findable, Accessible, Interoperable, and Reusable.
OGC’s member-driven consensus process creates royalty free, publicly available geospatial standards. Existing at the cutting edge, OGC actively analyzes and anticipates emerging tech trends, and runs an agile, collaborative Research and Development (R&D) lab that builds and tests innovative prototype solutions to members' use cases.
OGC members together form a global forum of experts and communities that use location to connect people with technology and improve decision-making at all levels. OGC is committed to creating a sustainable future for us, our children, and future generations.
Visit [ogc.org](http://ogc.org/) for more info on our work.

