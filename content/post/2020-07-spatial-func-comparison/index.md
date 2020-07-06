---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Comparison of Spatial Functions: PostGIS, Athena, PrestoDB, BigQuery vs RedShift"
subtitle: "A brief comparison of spatial functions supported by PostGIS, Athena, PrestoDB, BigQuery and Redshift"
summary: ""
authors: [yoong-shin]
tags: [AWS, Athena, RedShift, GCP, BigQuery, PrestoDB, guide]
categories: []
date: 2020-07-03T16:50:51+08:00
lastmod: 2020-07-03T16:50:51+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by [NASA](https://unsplash.com/@nasa) on [Unsplash](https://unsplash.com/photos/_SFJhRPzJHs)"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

We are moving our geospatial analysis to the cloud. As we are evaluating the various offerings by 
[AWS](https://aws.amazon.com/) and [Google Cloud Platform](https://cloud.google.com/), we wonder to what extent 
these cloud database products support spatial functions in comparison to [PostGIS](https://postgis.net).  

Being the most widely used extended PostgreSQL object-relational database system, PostGIS allows spatial objects to be stored in the database and offers a wide range of functions for their analysis and processing.

[AWS Athena](https://aws.amazon.com/athena/), [PrestoDB](https://prestodb.io/),
[Google BigQuery](https://console.cloud.google.com/bigquery), and [AWS Redshift](https://aws.amazon.com/redshift/) 
are included in our considerations. Direct links to the respective documentation of currently supported 
spatial functions are listed in the [References](#references) section at the end of this post.

Here is a summary of the comparison. 

### Geometry/Geography/Box Data Types
![](comp1-PostGIS-Data-Types.png)


### Table Management Functions 
![](comp2-Table-Management.png)


### Geometry Constructors
![](comp3-Constructors.png)


### Geometry Accessors
![](comp4-Accessors1.png)
![](comp4-Accessors2.png)


### Geometry Editors
![](comp5-Editors.png)


### Geometry Validation
![](comp6-Validation.png)


### Spatial Reference System Functions
![](comp7-Spatial-Reference-System.png)


### Geometry Input
####  _Well-Known Text (WKT)_
![](comp8a-Input-WKT.png)
####  _Well-Known Binary (WKB)_
![](comp8b-Input-WKB.png)
#### _Other Formats_
![](comp8c-Input-Others.png)


### Geometry Output
####  _Well-Known Text (WKT)_
![](comp9a-Output-WKT.png)
####  _Well-Known Binary (WKB)_
![](comp9b-Output-WKB.png)
#### _Other Formats_
![](comp9c-Output-Others.png)


### Operators
#### _Bounding Box Operators_
![](comp10a-Operators-Box.png)
#### _Distance Operators_
![](comp10b-Operators-Distance.png)


### Spatial Relationships
#### _Topological Relationships_
![](comp11a-Relationships-Topological.png)
#### _Distance Relationship_
![](comp11b-Relationships-Distance.png)


### Measurement Functions
![](comp12-Measurement.png)


### Geometry Processing
![](comp13-Processing1.png)
![](comp13-Processing2.png)


### Affine Transformations
![](comp14-Affine-Transformations.png)


### Clustering Functions
![](comp15-Clustering.png)


### Bounding Box Functions  
![](comp16-Bounding-Box.png)


### Linear Referencing
![](comp17-Linear-Referencing.png)


### Trajectory Functions
![](comp18-Trajectory.png)


### SFCGAL Functions
![](comp19-SFCGAL.png)


### Long Transaction Support
![](comp20-Long-Transaction.png)


### Aggregation 
![](comp21-Aggregation.png)


### MS Big Tiles
![](comp22-MS-Bing-Tiles.png)

Although AWS and Google Cloud Platform have started to support spatial functions in their product offerings, there 
are still quite some spatial functions missing as the time this post is written. Hopefully more of these currently
missing functions will be available soon. 
<br />
<br />
______________________
<br />
<a name="references">References</a>:
- [PostGIS Reference](https://postgis.net/docs/reference.html)
- [AWS Athena Spatial Functions](https://docs.aws.amazon.com/athena/latest/ug/geospatial-functions-list.html)
- [Presto DB Geospatial Functions](https://prestodb.io/docs/current/functions/geospatial.html)
- [Google BigQuery Geography Functions](https://cloud.google.com/bigquery/docs/reference/standard-sql/geography_functions)
- [AWS Redshift Spatial Functions](https://docs.aws.amazon.com/redshift/latest/dg/geospatial-functions.html)
<br />
<br />
