---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Paper on quality of BIM-GIS conversion"
subtitle: ""
summary: "Much work has been done on quality of geoinformation and interoperability between BIM and GIS. However, the intersection of the two - quality control of the conversion between BIM and GIS - remains uncharted"
authors: [admin]
tags: [bim, gis, quality, 3d city modelling, 3d geoinfo, paper, conference, events]
categories: []
date: 2019-09-26T08:35:16+08:00
lastmod: 2019-09-26T08:35:16+08:00
featured: false
draft: false
show_related: true
pager: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Combination of different types of errors results in multiple categories that are depending on the use case context. Source of the dataset (with modifications) used to generate the illustration: Institute for Applied Computer Science, Karlsruhe Institute of Technology (Häfele, 2011)."
  focal_point: ""
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [bim-gis]
---

{{< figure src="featured.png" title="Combination of different types of errors results in multiple categories that are depending on the use case context. Source of the dataset (with modifications) used to generate the illustration: Institute for Applied Computer Science, Karlsruhe Institute of Technology (Häfele, 2011)." numbered="false" lightbox="true" >}}

We published a new paper:

> Biljecki F, Tauscher H (2019): Quality of BIM-GIS conversion. _ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci._ IV-4/W8:35–42. [<i class="ai ai-doi-square ai"></i> 10.5194/isprs-annals-IV-4-W8-35-2019](https://doi.org/10.5194/isprs-annals-IV-4-W8-35-2019) [<i class="far fa-file-pdf"></i> PDF](/publication/2019-bim-gis-quality/2019-bim-gis-quality.pdf) <i class="ai ai-open-access-square ai"></i>

Much work has been done on quality of geoinformation and interoperability between BIM and GIS.
However, the intersection of the two - quality control of the conversion between BIM and GIS - remains uncharted.
This discussion paper, based on empirical results, is one of the first steps towards mapping out a framework on errors and quality control in the context of BIM–GIS interoperability.
In our work we focus on the conversion from IFC to CityGML, identifying several systematic errors potentially common and/or exclusive to the context of BIM–GIS conversion.
Besides exposing several faults pertaining to IFC-sourced 3D city models, we discuss their taxonomy and their potential impact when engaged in applications.
This paper is also relevant with respect to the growing popularity of conversion between IFC and CityGML, potentially aiding others to avoid many of the errors that can occur in the process and establishing directions to set up a benchmark to assess the performance of the interoperability workflows.

For more information please see the [paper](/publication/2019-bim-gis-quality/) (open access <i class="ai ai-open-access-square ai"></i>).

[![](page-one.png)](/publication/2019-bim-gis-quality/)


BibTeX citation:
```bibtex
@article{2019_bim_gis_quality,
 author = {Biljecki, F and Tauscher, H},
 doi = {10.5194/isprs-annals-IV-4-W8-35-2019},
 journal = {ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci.},
 pages = {35--42},
 title = {{Quality of BIM--GIS conversion}},
 volume = {IV-4/W8},
 year = {2019}
}
```

{{< figure src="c1-CityGML-3rd-2_cut.png" title="CityGML dataset obtained from IFC (storey of one building) with the approach developed within our project. Source of the input IFC dataset: BCA Singapore." numbered="false" lightbox="true" >}}

