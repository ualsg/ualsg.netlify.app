---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Impact of the pandemic on bus ridership in Singapore"
subtitle: "Featuring an urban data science project by our Master of Urban Planning students"
summary: "Featuring an urban data science project by our Master of Urban Planning students"
authors: ["Chen Bingling", "Liang Xiucheng", "Liu Lina", "Wen Ruiwen"]
tags: [teaching, analysis]
categories: []
date: 2021-05-31T08:43:28+08:00
lastmod: 2021-05-31T08:43:28+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Change of total bus passenger volume by planning area over one year (early 2020 vs early 2021)."
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Each year, [Master of Urban Planning](https://www.sde.nus.edu.sg/arch/programmes/master-of-urban-planning/curriculum/) students taking the module [DEP5111 Planning Technologies](https://www.sde.nus.edu.sg/arch/programme_article/dep5111-planning-technologies/) carry out group projects to demonstrate the attained data science skills and apply them in the urban context.

The article below features one of the projects completed in this semester by Chen Bingling, Liang Xiucheng, Liu Lina, and Wen Ruiwen.

This final group project was finished in early April 2021, focusing on the comparative analysis of public transportation (bus) passenger volumes just before the onset of the pandemic and the introduction of the safety measures (January 2020) and a year later, several months after many of the restrictions were progressively lifted.

Each group project, including this one, was carried out entirely using open data and open-source software.

We thank all the students in the class for their interesting projects.

***

### Abstract

The COVID-19 pandemic greatly impacted cities around the world in various aspects, e.g. resulting in the decrease of public transportation ridership. This study investigates the influence of COVID-19 on bus travel behavior across different land uses and planning areas in Singapore, and analyzes the bus stop recovery rate using an evaluation model. According to the data available at the time of the analysis, 92% of bus stops have not yet resumed to the stage of January 2020 in terms of passenger volume. The study reveals some notable results, e.g. after the strictest measures were lifted in June 2020, Marina South and the Southern Islands exhibited a sharp rise in traffic in July 2020. Nevertheless, in comparison with other planning areas, these locations still have a low recovery rate presumably partly due to the loss of international visitors. In relative terms, the residential areas tend to have a better recovery performance. However, the institutional and business related land uses are still under the expected lines, partially because a large portion of the population has transitioned to working and learning from home.
The results also suggest an inverse relationship between the share of residents living in private housing and the recovery rate of bus passenger volume at the scale of a planning area.

{{< figure src="shawnanggg-UmxIsHNZvTs-unsplash.jpg" caption="Photo by [shawnanggg](https://unsplash.com/@shawnanggg) on [Unsplash](https://unsplash.com/s/photos/covid-singapore-bus)." >}}

### Background

Starting in April 2020, [circuit breaker measures](https://en.wikipedia.org/wiki/2020–21_Singapore_circuit_breaker_measures) have been implemented in preventing further spread of COVID-19. The measures were beneficial and successful, but as everywhere around the world, they had an [impact on transportation](https://en.wikipedia.org/wiki/COVID-19_pandemic_in_Singapore#Transportation). The Land Transport Authority reported that average daily ridership for buses and trains fell by 34.5% – an 11-year low[^3].
The city-state was not alone in experiencing plummeting ridership, e.g. in Washington DC, metrorail, bus ridership declined by 75%[^1]; in London, the usage of public transportation dropped by 40%[^2].

[^1]: WMATA. [Metro and Covid-19: Steps we’ve taken](https://www.wmata.com/service/status/details/COVID-19.cfm). 2020 [accessed on 2 April 2020].
[^2]: Harrabin, B.R. (25 April 2020). [Coronavirus: Transport usage will change after lockdown](https://www.bbc.com/news/business-52414376). BBC News.
[^3]: Tan, C. (10 February 2021). [Bus, train ridership in Singapore falls to 11-year low amid Covid-19 pandemic](https://www.straitstimes.com/singapore/transport/bus-train-ridership-in-singapore-falls-to-11-year-low-amid-covid-19-pandemic). The Straits Times. 

The aim of this study is to understand the changes of bus ridership over the period of COVID-19 and to what extent has people’s movement recovered from the pandemic.
The analysis focuses on Singapore’s planning areas and land use, and it also analyzes relationships with demographics.

### Data and Method

This study is conducted by investigating the passenger volume changes by months in 2020 and other factors such as land use and the characteristics of planning areas. Based on the comparison of the passenger volume and flow direction in January 2021 with the same period of 2020, an evaluation model of passenger volume recovery for each bus stop is built and implemented to identify the changing behavior of bus ridership. It also aims to discuss the implications for future planning of bus stops and transport networks.

There are two key data sources used in this analysis: (i) origin destination data from the [Land Transport Authority](https://datamall.lta.gov.sg); and (ii) Land Use and Planning area boundaries according to the Master Plan of the [Urban Redevelopment Authority](https://data.gov.sg/search?organization=urban-redevelopment-authority).
Further, the demographic data by the [Singapore Department of Statistics](https://www.singstat.gov.sg) has been used to attempt to associate the change in public transport ridership with demographics.

In brief, we first calculate and aggregate the passenger volumes by land use and planning area according to a 50m buffer around each bus stop, and observe the general trends.
Afterwards, we calculate the rate of change in total passenger volume (sum of tap-in and tap-out) related to the previous month and its change rate.


### Results

#### Planning area and land use type change rate by month

{{< figure src="1.png" id="fig-1" caption="Rate of change of bus ridership by planning area." numbered="true" >}}

In Figure [1](#fig-1), we summarize the rate of change of passenger volume in each planning area and visualize with heatmap.
There is a visible change during and after the period April-May 2020 when the most stringent measures were in place.
Marina South and Southern Islands exhibit explosive growth in volumes in July 2020.

Using the same method, we calculate the change rate of land use.

{{< figure src="2.png" id="fig-2" caption="Rate of change of bus ridership by land use." numbered="true" >}}

In Figure [2](#fig-2), bus stops associated with the land use of Beach Area (according to the URA Master Plan) have taken the lead in a positive upward trend of total passenger volume in May 2020. These are mostly locations close to residential areas (e.g. East Coast Park), and it can be assumed that residents preferred close seaside parks for leisure activities during Phase I.

In the meantime, the Educational Institution land use exhibited the most significant increase while the Port/Airport only showed a slight increase in June 2020. This phenomenon can be explained by the large number of students resuming class while many jobs are still in the work from home mode, and obviously because of the severely restricted international travel.

#### Period-over-period comparison of total passenger volume and traveling direction

We worked on understanding how the mutual flow of passengers has changed between land uses using the Sankey diagram. Considering that land use types with small absolute values of flow rate will show thin lines that are difficult to distinguish, 11 land-use types with large passenger flow rates are chosen here for graphical representation, for each period separately.

{{< figure src="3.png" id="fig-3" caption="Flow of Passenger Traffic by land use type in January 2020. Data: LTA & URA, 2021." numbered="true" >}}

{{< figure src="4.png" id="fig-4" caption="Flow of Passenger Traffic by land use type in January 2021. Data: LTA & URA, 2021." numbered="true" >}}

Comparing Figure [3](#fig-3) and Figure [4](#fig-4), we can see that the volume flowing from residential to transport facilities decreases, the volume flowing from park to business2 increases significantly, and the flow from commercial to business decreases remarkably.

Next, we compare the total passenger volumes by planning area of Jan 2020 and Jan 2021.

{{< figure src="5.png" id="fig-5" caption="Changes of total volume by different land use." numbered="true" >}}

Figure [5](#fig-5) suggests that Yishun and Bukit Batok, which are predominantly residential areas, have a smaller difference in total trip value than Woodlands and Bukit Panjang in comparison to the same period last year, and have shown better recovery rates.
Meanwhile, Kallang, Jurong West, Jurong East, Houguang, and Geylang, etc. show a similar trend. It is assumed that the demographic structure of the area may have some influence on the degree of traffic volume recovery.

#### Recovery performance

##### Recovery performance analysis by bus stop, land use and town

The recovery performance of bus stops is defined by the ratio of the total passenger volume in January 2021 to the total passenger volume in January 2020. Firstly, we calculated the recovery rate of each bus stop and observed the overall distribution through density graph.

{{< figure src="6.png" id="fig-6" caption="Frequency distribution of different recovery rates of bus stops in Singapore." numbered="true" >}}

Figure [6](#fig-6) indicates that the recovery rate of 92% bus stops is below one, meaning that by Jan 2021 their total tap in and tap out volume has not recovered to the levels in Jan 2020, before the pandemic. The recovery rate of most bus stops concentrates between 0.625 and 0.875, and some bus stops experienced more severe loss in passenger volumes, with their recovery rate below 0.5. Dividing the total trips of each bus stop into different land use and planning areas according to their land area percentage of the 50m buffer area, we are able to calculate the recovery rates of different land use and planning areas.

{{< figure src="7.png" id="fig-7" caption="Recovery rate of bus riding behaviour by land use." numbered="true" >}}

In Figure [7](#fig-7), the recovery rates of all land uses, except for beach area are below 0.625, and it is clear that residential as well as industrial related land use tend to have better recovery performance, while some institutional or tourism related land uses, such as airport or hotel, unsurprisingly still have relatively low recovery rates. The recovery rates of educational institutions, commercial and business parks are not as high as expected, which may be explained by the work from home guidelines. These institutions and their staff have more or less adapted to remote working or learning mode, so they tend to adopt a cautious attitude even if the pandemic has eased.

{{< figure src="8.png" id="fig-8" caption="Recovery rate of bus riding behaviour by planning area." numbered="true" >}}

{{< figure src="9.png" id="fig-9" caption="Recovery rate of bus riding behaviour by planning area. Planning areas without bus stops are excluded from the spatial dataset." numbered="true" >}}

Moving to planning areas, it is indicated in Figure [8](#fig-8) and Figure [9](#fig-9) that there are stark differences in the recovery rate of different planning areas, ranging from 0.283 to 0.939. Hit by the decrease of tourists, Southern Islands (i.e. the planning area in which Sentosa is located) has the lowest recovery rate, while new towns with a large percentage of residential land use, such as Punggol, Paya Lebar, and Yishun recovered faster than other towns.

Besides land use, we analyze whether socio-demographic features may explain the variances of recovery rates across different towns.
We joined the data of age (share of seniors), gender ratio (share of female population), population density, as well as the percentage of residents living in private housing, and computed correlations.

{{< figure src="10.png" id="fig-10" caption="Recovery rate, senior population share, population density, private housing rate, and gender ratio." numbered="true" >}}

The results in Figure [10](#fig-10) suggest that population density has the most significant impact on recovery rate, and the more populated a town is, the faster it may recover from the pandemic in terms of bus stop passenger volume. The percentage of residents living in private housing has a moderate negative correlation with recovery rate, possibly because other private transport modes are more accessible to the residents in planning areas with more private dwellings.

##### Recovery performance evaluation and adjustment recommendation of bus stops

Combining the results of recovery rates of planning area, land use and each bus stop, as well as the their mutual flow of passengers, we are able to conduct a bus stop recovery performance evaluation.
Each bus stop was given a categorical score (from A to E) to indicate its overall recovery rank based on the aforementioned aspects.
We visualized the bus stops and their ranks in the map and observed the spatial relationships.

{{< figure src="13.png" id="fig-13" caption="Recovery rank of bus stops for a part of Singapore." numbered="true" >}}

{{< figure src="14.png" id="fig-14" caption="Recovery rank of bus stops (only D and E)." numbered="true" >}}

Figures [11](#fig-13) & [12](#fig-14) show that bus stops of rank A or B are more equally distributed, while bus stops of rank C or D seem to concentrate in areas such as CBD, Bukit Timah and Tuas. Areas with a notable share of bus stop of A and B ranks could well preserve and maintain the existing bus stops, while areas with high concentration of bus stops of D and E rank could be considered to combine some of the bus stops or adjust their locations until the impacts of the pandemic are relieved.


### Conclusions

In this exercise, we observed how the pandemic has influenced public transit behaviours in terms of both robustness and resilience. As almost everywhere around the globe, measures introduced to combat the pandemic have greatly influenced people’s transit travel behavior, as shown by the rate of change in planning area and land use. In terms of robustness, we found that certain land use and planning areas experienced the most severe strikes in passenger volumes during May 2020 and July 2020, when the pandemic and the restriction reached their peaks. The locations where people tend to travel to by bus have also changed, as shown by the change in the ranking of destination land use types.

In terms of resilience, we found out that the total bus trips have not yet returned to the pre-pandemic level in all planning areas as well as land uses, in spite of some differences in their recovery rate. Therefore, as an urban planning exercise, we conducted a recovery performance evaluation on bus stops.

### Limitations

This analysis is not without limitations.
The most important ones are:

1. We assumed that all changes in bus trips were the effect of the pandemic and did not fully consider other factors, such as the bus operator’s own adjustments to stops and routes, and other factors that are simply unrelated to the pandemic and measures.
1. We gave the same weight to all site types, and the passenger volume to each site was assigned with the proportion of the footprint of the site type within the service radius, without taking into account the relatively higher possibility of land use like commercial and residential as travel destinations in real life, so the results may have some deviations from the actual outcomes.
1. In the correlation analysis of the factors influencing the recovery rate in the region, the amount of data that can be used is limited and the sample size is relatively small, so the correlation coefficients may not be entirely indicative.

### Acknowledgements

This student project was carried out as part of module [DEP5111 Planning Technologies](https://www.sde.nus.edu.sg/arch/programme_article/dep5111-planning-technologies/) in the [Master of Urban Planning](https://www.sde.nus.edu.sg/arch/programmes/master-of-urban-planning/curriculum/), which is conducted by the [NUS Urban Analytics Lab](/).
The open data sources by LTA, URA and SingStat used in this analysis are gratefully acknowledged.

### Further reading

If you find this article of interest, have a look also at [our April 2020 analysis using carpark data]({{< relref "/post/2020-04-covid-19-singapore-impact-urban-data" >}}).

