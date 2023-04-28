---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Developing a multiview spatiotemporal model based on deep graph neural networks to predict the travel demand by bus
subtitle: ''
summary: ''
authors:
- tianhong
- Zhengdong Huang
- Wei Tu
- filip
- Long Chen
tags: []
categories: []
date: '2023-04-26'
lastmod: 2023-04-27T21:18:19+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-04-27T19:18:19.531210Z'
publication_types:
- '2'
abstract: 'The accurate prediction of travel demand by bus is crucial for effective urban mobility demand management. However, most models of travel demand prediction by bus tend to focus on the bus’s spatiotemporal dependencies, while ignoring the interactions between buses and other transportation modes, such as metros and taxis. We propose a Multiview Spatiotemporal Graph Neural Network (MSTGNN) model to predict short-term travel demand by bus. It emphasizes the ability to capture the interaction dependencies among the travel demand of buses, metros, and taxis. Firstly, a multiview graph consisting of bus, metro, and taxi views is constructed, with each view containing both a local and global graph. Secondly, a multiview attention-based temporal graph convolution module is developed to capture spatiotemporal and cross-view interaction dependencies among different transport modes. Especially, to address the uneven spatial distributions of features in multiview learning, the cross-view spatial feature consistency loss is introduced as an auxiliary loss. Finally, we conduct intensive experiments using a real-world dataset from Shenzhen, China. The results demonstrate that our proposed MSTGNN model performs better than the existing models. Ablation experiments validate the contributions of various modes of transportation to the improvement of the model’s performance.'
publication: '*International Journal of Geographical Information Science*'
doi: 10.1080/13658816.2023.2203218
---
