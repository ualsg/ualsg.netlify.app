---
title: Translating street view imagery to correct perspectives to enhance bikeability
  and walkability studies

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- koichi
- matias
- Xianjing Han
- Roger Zimmermann
- filip

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-08-26'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-09-01T14:57:51.718357Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*International Journal of Geographical Information Science*'
publication_short: ''

doi: 10.1080/13658816.2024.2391969

abstract: 'Street view imagery (SVI), an emerging geospatial dataset, is useful for evaluating active transportation infrastructure, but it faces potential biases from its vehicle-based capture method, diverging from pedestrians’ and cyclists’ perspectives. Existing literature lacks both an examination of these biases and a solution. This study identifies and quantifies these biases by comparing conventional SVI with views from the road shoulder/sidewalk. To mitigate such perspective biases, we introduce a novel framework with generative adversarial network (GAN)-based image generation models (Pix2Pix and CycleGAN), an image regression model (ResNet-50), and a tabular model (LightGBM). Experiments assessed model effectiveness in translating car-centric views to those from pedestrian and cyclist perspectives. Results show significant differences in semantic indicators (e.g. green view index) between road center and road shoulder/sidewalk SVI, with low Pearson’s correlation coefficients r (0.35–0.55 for road shoulders and 0.45–0.47 for sidewalks) indicating bias. The framework succeeded in creating realistic images and aligning pixel ratios between perspectives, achieving strong correlation coefficients (0.81 for road shoulders and 0.83 for sidewalks), thus reducing bias. This work contributes by providing a scalable and model-agnostic approach to produce accurate SVIs for urban planning and sustainability, setting a foundation for improving bikeability and walkability assessments and promoting active transportation.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
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

