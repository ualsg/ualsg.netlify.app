---
title: Roofpedia

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---

{{< roofpedia >}}

## Roofpedia -- Mapping Roofscapes with AI

### Explore Sustainable Roofscapes Around the World

Roofpedia is an open registry of sustainable roofscapes around the world. It uses deep convolutional neural network to detect sustainable roof typologies from satellite images. Building footprints identified with solar panels or rooftop greens are tagged automatically, and the results are visualized above.

{{< figure src="feature.jpg" title="Roofpedia in a nutshell." >}}

## The Roofpedia Index

The Roofpedia Index is a measure of the penetration of sustainable roof typologies in major cities around the world. Solar roofs and Green roofs mapped by Roofpedia are compared against the total number of buildings and areas of the buildings in a city. Aggregate scores are calculated for both solar and green coverage and cities are ranked with an combined score.

Click on city names to visit them on map.

| **Rank**  | **City**              | **Buildings**     | **Solar Roofs**   | **%SR Count**     | **%SR Area**  | **Solar Score**   | **Green Roofs**   | **%GR Count**     | **%GR Area**  | **Green Score**   | **Overall Score**     |
|------ |---------------    |-----------    |-------------  |------------   |-----------    |-------------  |-------------  |------------   |-----------    |-------------  |---------------    |
| 1     | [Zurich][Zurich]          | 18440         | 838           | 4.5           | 12.9          | 86            | 5760          | 31.2          | 41.6          | 100           | 93                |
| 2     | [Berlin][Berlin]          | 28677         | 809           | 2.8           | 11.3          | 61            | 3899          | 13.6          | 24.8          | 51            | 56                |
| 3     | [Las Vegas][Las Vegas]        | 20389         | 805           | 3.9           | 17.3          | 93            | 192           | 0.9           | 7.8           | 9             | 51                |
| 4     | [Phoenix][Phoenix]        | 15217         | 576           | 3.8           | 14.1          | 81            | 245           | 1.6           | 9.9           | 13            | 47                |
| 5     | [Melbourne][Melbourne]        | 16809         | 486           | 2.9           | 17.3          | 81            | 258           | 1.5           | 8.4           | 11            | 46                |
| 6     | [New York][New York]      | 34385         | 677           | 2.0           | 9.4           | 46            | 1924          | 5.6           | 17.2          | 28            | 37                |
| 7     | [Copenhagen][Copenhagen]      | 15505         | 354           | 2.3           | 9.0           | 48            | 735           | 4.7           | 13.1          | 22            | 35                |
| 8     | [Paris][Paris]            | 74014         | 1507          | 2.0           | 9.1           | 45            | 2766          | 3.7           | 11.2          | 18            | 32                |
| 9     | [San Diego][San Diego]        | 28303         | 237           | 0.8           | 7.4           | 27            | 373           | 1.3           | 11.0          | 14            | 20                |
| 10    | [Los Angeles][Los Angeles]    | 50978         | 384           | 0.8           | 6.3           | 22            | 419           | 0.8           | 4.7           | 6             | 14                |
| 11    | [San Jose][San Jose]          | 182314        | 732           | 0.4           | 4.9           | 14            | 2650          | 1.5           | 10.2          | 13            | 13                |
| 12    | [Seattle][Seattle]        | 81044         | 263           | 0.3           | 5.4           | 15            | 347           | 0.4           | 5.6           | 6             | 10                |
| 13    | [Portland][Portland]          | 122900        | 482           | 0.4           | 4.2           | 11            | 302           | 0.2           | 3.7           | 3             | 7                 |
| 14    | [San Francisco][San Francisco]    | 165814        | 560           | 0.3           | 3.9           | 10            | 389           | 0.2           | 2.6           | 2             | 6                 |
| 15    | [Vancouver][Vancouver]        | 163818        | 145           | 0.1           | 1.6           | 0             | 108           | 0.1           | 1.0           | 0             | 0                 |0               |


Disclaimer: Vancouver is green! Just not roof green compared to the top cities in the list.

More cities are getting added to Roofpedia as their satellite data become available. If you'd like to contribute satellite images to expand Roofpedia, please email the author at abraham@nus.edu.sg

Full data and code of Roofpedia can be accessed at the [GitHub repo](https://github.com/Iceofsky/Roofpedia).

A preprint of the paper can be found on [arXiv](https://arxiv.org/abs/2012.14349).

```
@misc{wu2020roofpedia,
  title={Roofpedia: Automatic mapping of green and solar roofs for an open roofscape registry and evaluation of urban sustainability}, 
  author={Abraham Noah Wu and Filip Biljecki},
  year={2020},
  eprint={2012.14349},
  archivePrefix={arXiv},
  primaryClass={cs.CY}
}
```




[Zurich]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.94/47.37444/8.52924

[Berlin]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.93/52.51752/13.3837

[Las Vegas]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.5/36.13763/-115.15459

[Phoenix]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.5/33.43687/-112.03097

[Melbourne]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.98/-37.81802/144.94817

[New York]:https://api.mapbox.com/styles/v1/iceofsky1/cki2tjlpr60yz19p95fcqr9h9.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q

[Copenhagen]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.93/55.68293/12.56875

[Paris]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.94/48.85579/2.34247

[San Diego]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.8/32.71559/-117.1766

[Los Angeles]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.64/34.04272/-118.19739

[San Jose]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.7/37.33137/-121.88839

[Seattle]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12/47.60711/-122.33685

[Portland]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.5/45.52039/-122.67767

[San Francisco]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12.5/37.77993/-122.42131

[Vancouver]:https://api.mapbox.com/styles/v1/iceofsky1/ckkaqwtr500v317r01y46xp6r.html?fresh=true&title=view&access_token=pk.eyJ1IjoiaWNlb2Zza3kxIiwiYSI6ImNraTF4ejIxaDBxNGgycm1zd3ZvMThwOGMifQ.-QrGKalxvWk3sY7BqDbI1Q#12/49.26528/-123.11271
