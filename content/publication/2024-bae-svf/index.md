---
title: A panorama-based technique to estimate sky view factor and solar irradiance
  considering transmittance of tree canopies

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- kunihiko
- koichi
- marcel
- filip

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-09-13'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-09-15T08:03:47.068031Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Building and Environment*'
publication_short: ''

doi: 10.1016/j.buildenv.2024.112071

abstract: 'Street-view-based techniques for assessing the sky view factor (SVF) and solar irradiance under trees are gaining attention as tools for evaluating trees as nature-based solutions to mitigate urban heat risks. Although these metrics significantly depend on the morphology of trees and resulting canopy transmittance, an existing approach, termed the Solid Canopy Method (SCM), assumes zero transmission and has not accounted for these variations. This paper advances the computation of both metrics, improving their accuracy and application — we developed the Transmissive Canopy Method (TCM), a panorama-based approach that integrates semantic segmentation and binarization to evaluate SVF and solar irradiance while accounting for transmittance of tree canopies. Using a study area on a university campus in Singapore, we collected data on solar irradiance and 360°imagery to validate our method. The results indicated improved accuracy with MAE, RMSE, and R values of 77.8 Wm−2, 105.0 Wm−2 and 0.90, respectively — significantly outperforming the SCM. We showcased two use cases of our method: (1) high-resolution mapping of SVF and solar irradiance in a field with trees, and (2) walking route optimization considering sunlight exposure. Our findings highlight the strong capability of our TCM to evaluate the effects of trees in mitigating urban heat more accurately than the existing method. Additionally, the TCM has potential applications in urban planning and management, enabling strategic tree planting prioritizing areas lacking sufficient shading and developing tools for optimizing walking routes to minimize sunlight exposure.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: 'https://github.com/kunifujiwara/TreeShadeMapper'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

