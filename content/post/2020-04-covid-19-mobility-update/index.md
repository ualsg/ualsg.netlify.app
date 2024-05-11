---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Updated plots on the current mobility situation around the world"
subtitle: "An update to our transit visualisations using the latest available data"
summary: ""
authors: [filip]
tags: [analysis]
categories: []
date: 2020-04-24T08:50:53+08:00
lastmod: 2020-04-24T08:50:53+08:00
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
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

About two weeks ago, we published
[an article]({{< ref "/post/2020-04-covid-19-singapore-impact-urban-data/index.md" >}}) on how Singapore has responded to the new stringent preventive measures against COVID-19, including a comparison with dozens of other cities around the world.

We have used data from [Citymapper](https://citymapper.com), i.e. the [Citymapper Mobility Index](https://citymapper.com/cmi), which indicates the daily change of the city moving compared to the usual trends (the index is calculated by comparing trips planned in the Citymapper app to a recent typical usage period).
Considering that the dataset is continuously updated, it is also time to update some of the plots.

The first one suggests that the intensity of transit remained low in Singapore after it plunged following the introduction of the [_circuit breaker_](https://www.gov.sg/article/what-you-can-and-cannot-do-during-the-circuit-breaker-period).
Still, it has further decreased by a few percents (this will also become visible in the final visual in this article).

{{< figure src="cmi-2020-04-23.png" title="" lightbox="true" >}}

Transit in Singapore is now around the world average.
Seoul and Hong Kong remained the least affected in the sample of 41 cities.
Nevertheless, their transit volume is at about a third than the usual levels, which is still an enormous drop.

{{< figure src="cmi-2020-04-23_multi-city.png" title="" lightbox="true" >}}

Another look at the same dataset, with each city illustrated separately:

{{< figure src="cmi-2020-04-23_multi-city_panels.png" title="" lightbox="true" >}}

And finally, the change in the past two weeks is visualised, which may be a good indicator of the recent events, such as the introduction or relaxation of measures.
The plot compares the situation on Wednesday 8 April (second day of the new stringent measures in Singapore) with the one on Wednesday 22 April 2020.
This time (in comparison with [the last version of the same plot]({{< ref "/post/2020-04-covid-19-singapore-impact-urban-data/index.md" >}})), no city covered in the dataset has experienced a radical change.

{{< figure src="cmi-2020-04-23_dumbbell.png" title="" lightbox="true" >}}

### Acknowledgements 

Thanks to [Citymapper](https://citymapper.com/cmi) for releasing and maintaining this dataset.

### Alternative data

In the meantime, Apple [made their aggregated navigation data from Maps available](https://www.apple.com/sg/newsroom/2020/04/apple-makes-mobility-data-available-to-aid-covid-19-efforts/) for [download](https://www.apple.com/covid19/mobility/).
It also includes Singapore, and it might be analysed in some future article.
