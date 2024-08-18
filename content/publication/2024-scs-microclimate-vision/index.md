---
title: 'Microclimate Vision: Multimodal prediction of climatic parameters using street-level
  and satellite imagery'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- kunihiko
- maxim-khomiakov
- winston
- marcel
- filip

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-08-17'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-08-18T01:02:58.004574Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Sustainable Cities and Society*'
publication_short: ''

doi: 10.1016/j.scs.2024.105733

abstract: 'High-resolution microclimate data is essential for capturing spatio-temporal heterogeneity of urban climate and heat health management. However, previous studies have relied on dense measurements that require significant costs for equipment, or on physical simulations demanding intensive computational loads. As a potential alternative to these methods, we propose a multimodal deep learning model to predict microclimate at a high spatial and temporal resolution based on street-level and satellite imagery. This model consists of LSTM and ResNet-18 architectures, and predicts air temperature (T_air), relative humidity (RH), wind speed (v), and global horizontal irradiance (GHI). For our study area situated at a university campus in Singapore, we collected microclimate data, street-level and satellite imagery. We conducted extensive experiments with our collected dataset to showcase our model’s predictive capabilities and its practical use in generating high-resolution microclimate maps. Our model reported RMSE at 0.95 °C for T_air, 2.57% for RH, 0.31 m/s for v, and 225 W/m2 for GHI. Furthermore, we observed a contribution of imagery inputs to higher accuracy by comparing models with and without such inputs. We identified hot spots at a high spatio-temporal resolution, indicating its application for issuing real-time heat alerts. Our models are released openly at the microclimate-vision GitHub repository (https://github.com/kunifujiwara/microclimate-vision).'

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

