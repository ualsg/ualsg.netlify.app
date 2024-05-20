---
title: Predicting building characteristics at urban scale using graph neural networks
  and street-level context

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- binyu
- pengyuan
- Nikola Milojevic-Dupont
- filip

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-18'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-05-19T19:50:18.227386Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Computers, Environment and Urban Systems*'
publication_short: ''

doi: 10.1016/j.compenvurbsys.2024.102129

abstract: 'Building characteristics, such as number of storeys and type, play a key role across many domains: interpreting urban form, simulating urban microclimate or modelling building energy. However, geospatial data on the building stock is often fragmented and incomplete. Here, we propose a novel and easily adaptable method to predict building characteristics in diverse cities, which attempts to mitigate such data gaps. Our method exploits the geospatial connectivity between street-level urban objects and building characteristics by employing graph neural networks, as they can model spatial relationships and leverage them for predictions. We apply this approach in three representative cities (Boston, Melbourne, and Helsinki) that offer a variety of building features as prediction targets (storeys, types, construction period and materials) and diverse urban environments as predictors. Overall, the magnitude of errors is acceptable for a series of use cases. In the prediction of building storeys, an average of 81.83% buildings in three cities have less than one-storey prediction error. We also find that the prediction of building type achieves an average of 88.33% accuracy across three cities. Meanwhile, an average of 70.5% of buildings are correctly classified by construction period in Melbourne and Helsinki, and the building material prediction accuracy is 68% in Helsinki. The results confirm that our approach is adaptable across different urban environments because comparable performance is achieved in the other two cities. Further, we assess the impact of varying local data availability on model performance. Our findings underscore the feasibility of the method in scenarios with sparse building data (10%, 30% and 50% availability). Our graph-based approach advances research on filling in incomplete building semantics from existing datasets, and showcases the potential to enable 3D city modelling. Given the broad applicability of the approach to predicting many building characteristics, diverse downstream applications exist, such as enhancing contemporary urban studies (e.g. exploring streetscapes) and facilitating the development of 3D GIS (e.g. maintaining and updating 3D building settings).'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: 'https://github.com/binyulei/gnn-building-characteristics-prediction'
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

