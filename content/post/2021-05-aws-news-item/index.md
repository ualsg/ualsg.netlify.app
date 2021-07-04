---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NUS Urban Analytics Lab scales research globally with AWS"
subtitle: "UAL’s AWS-supported urban toolkits and databases were featured on Amazon’s Public Service blog"
summary: "UAL’s AWS-supported urban toolkits and databases were featured on Amazon’s Public Service blog"
authors: [admin]
tags: [press release, research, paper, news, urban morphology]
categories: []
date: 2021-05-23T06:43:28+08:00
lastmod: 2021-05-23T06:43:28+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "OpenStreetMap contributors."
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Our ongoing research on developing a toolkit and dataset of urban morphology was featured as a [news item](https://aws.amazon.com/blogs/publicsector/nus-urban-analytics-lab-scales-research-globally-aws/) by Amazon at their [AWS Public Sector Blog](https://aws.amazon.com/blogs/publicsector/).

We thank AWS for their support and for writing about our project.

The [full release](https://aws.amazon.com/blogs/publicsector/nus-urban-analytics-lab-scales-research-globally-aws/) is copied below.

***

The Urban Analytics Lab at the National University of Singapore (NUS) spearheads research in geospatial data analysis and three-dimensional (3D) city modelling. The lab’s work underpins the development of smart cities and provides scientists, architects, urban planners, and real estate developers with data insights. These insights help parties make informed decisions about projects ranging from energy modelling to urban farming. To meet rising global demand for its data analytics and planning tools, Urban Analytics Lab turned to Amazon Web Services (AWS).

Following its inception in 2019, Urban Analytics Lab used a single server on the NUS campus to power its research. However, the limited capabilities of the infrastructure meant that researchers were constrained to contain their projects or run them on a smaller scale. The research group selected AWS not only because it was on the NUS IT department’s pre-approved cloud vendor list, but because of its track record supporting academic research and providing generous cloud credits to help institutions spark innovation.

AWS offered Urban Analytics Lab the global, on-demand scalability and availability it needed to expand its research. Researchers could adopt AWS services quickly to help them conduct research more efficiently.

Today, Urban Analytics Lab uses AWS as the foundation for most of its investigations. Much of the lab’s research is based on OpenStreetMap, a crowdsourced geospatial dataset. Using Amazon Relational Database Service (Amazon RDS), researchers imported OpenStreetMap data for the entire world into a PostGIS database that they have upgraded with custom procedures for processing and analysis.

Hosting the PostGIS database on Amazon RDS enables researchers to work on an unprecedented scale. They can conduct more thorough and in-depth analysis and apply it to almost any geographic location.

Urban Analytics Lab also used Amazon RDS and Amazon Elastic Compute Cloud (Amazon EC2) to create a 10 TB geospatial warehouse from which it derives quantitative properties of buildings from urban areas all around the world, including densities, volumetric compactness, and complexity of urban landscapes. The resulting Global Building Morphological Indicator dataset, spanning 500 million buildings and counting, will provide the most consistent and comprehensive set of metrics yet for buildings and the built environment around the world. Such a dataset may be used by urban planners and energy and climate researchers to understand the urban fabric and interplay with phenomena such as emissions, population, and economic data.

Scientists at the lab plan to apply machine learning (ML) to these indicators to predict the heights of individual buildings around the world, enhancing the input OpenStreetMap dataset, which is still largely confined to two-dimensional (2D) data. Adding height information will support further analyses and use cases, such as noise pollution estimations and wind flow analyses. Amazon EC2 and Amazon SageMaker will be used to build, train, and manage the models while the experiments are conducted, and Amazon Simple Storage Service (Amazon S3) will be used to store and share the intermediate, secondary, and final results.

The scalability the research group achieved by using AWS means that Urban Analytics Lab no longer needs to invest in its own high-performance and high-capacity servers and can redeploy those funds to other areas of the organization. And, since AWS offers secure access free of internal VPN restrictions, research teams can work virtually anywhere—a key advantage particularly during the COVID-19 pandemic.

With AWS, researchers can perform analysis and generate urban morphological data on a global scale, benefitting both its own research efforts and relevant studies in peripheral fields.

Learn more about the cloud for research and the cloud for higher education.
