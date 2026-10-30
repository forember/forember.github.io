---
layout: post
title:  "Public Transit Access to Spanish-Language HIV Services"
date:   2026-10-30 12:18 -0400
categories: portfolio
---

<style>
  @media (width >= 740px) {
    body {
      font-size: 120%;
    }
  }
  table {
    margin: 0px;
    margin-bottom: 4px;
    font-size: 80%
  }
  .float {
    float: right;
    width: 50%;
    margin: 4px;
  }
  .border {
    border: solid #e8e8e8 1px;
    padding: 4px;
  }
  .caption {
    margin-top: 0px;
    font-size: 80%;
  }
  .column {
    margin-left: 0px;
    margin-right: 0px;
  }
</style>

![Map of Need and Access](/assets/images/NeedAccessLayout.png){: class="border" style="width: calc(100% - 10px); height: auto;"}
<span class="border caption" style="display: block; margin-top: 4px;"><strong>Figure 1.</strong> Access and need levels are mapped by US Census tract. Of particular note are the magenta areas, representing tracts with high need for public transit access to Spanish-language HIV services—defined as areas with above county average HIV rate, population of adults in poverty who speak Spanish, and population of Spanish speakers with limited English who do not drive to work—but low access to these services—defined as being more than 45 minutes by walking and public transit from an HIV clinic with staff who speak Spanish.</span>

| Tract of Interest                           | 17.01 &amp; 17.02  | 19.10  | 38.10  |
| ------------------------------------------- | ------------------ | ------ | ------ |
| People who Speak Spanish                    | 37.8%              | 35.4%  | 44.7%  |
| … of whom do not Speak English “Very Well”  | 88.0%              | 77.5%  | 82.8%  |
| … of whom do not Drive Alone to Work        | 52.2%              | 62.2%  | 56.4%  |
| People with Income Below Poverty Level      | 25.5%              | 22.3%  | 16.6%  |

<p class="border caption"><strong>Table 2.</strong> Population statistics for four tracts highlighted in figure 1 above.</p>

Highlighted in magenta in figure 1 above are areas with high need for public transit access to Spanish-language HIV services—defined as areas with above county average HIV rate, population of adults in poverty who speak Spanish, and population of Spanish speakers with limited English who do not drive to work—but low access to these services—defined as being more than 45 minutes by walking and public transit from an HIV clinic with staff who speak Spanish. Four specific US Census tracts are highlighted and summarized in table 2 below. The areas with the greatest need and lowest access tend to be on the periphery of Charlotte proper. Some areas closer to Uptown with high need do have good access, whereas areas in north, west, and southeast Mecklenburg County have low access but also low need.

Areas with high need for but low access to Spanish-language HIV-related services could be well served by mobile HIV clinics with staff who speak Spanish. Mobile healthcare services are important stopgaps for meeting need in areas that otherwise would not have good access to those healthcare services. In addition, other providers in these areas may consider expanding the HIV-related services they provide or improving the accessibility of their services to those who do not speak English.

Binary measures of need and access were used here to determine areas of interest, so further research could determine relative level of need and access. Further research could also potentially include collaboration with the qualifying providers to further identify underserved areas, as well as collaboration with providers in high need areas to improve the accessibility of their services to those who do not speak English.

- - -

## Background

![Map of Service Area](/assets/images/03ServiceAreaLayout.png){: class="float border"}
<span class="float border caption"><strong>Figure 2.</strong> The area accessible within 45 minutes by walking and public transit from an HIV clinic with staff who speak Spanish is mapped in blue. The Charlotte Area Transit System bus and tram lines are mapped in red. Map by Emberlynn McKinney.</span>
Language can be a key barrier to accessing quality healthcare, and so some healthcare providers ensure that they have people on staff who speak Spanish, either to directly provide care, or to translate between a provider and the patient. Language is especially important for effectively navigating the nuances of HIV prevention and treatment, often requiring extended counseling with a provider to land on a prevention or treatment plan. Areas of Mecklenburg County, North Carolina have very high rates of HIV infection. Roughly 3% of residents of ZIP code 28206—encompassing the Double Oaks, Tryon Hills, and Sugar Creek neighborhoods—are living with HIV. Mecklenburg also has over 100,000 adults who speak Spanish, 59% of whom do not speak English very well or at all. Many of these individuals also do not rely on a personal vehicle for getting to work or other daily activities. The Charlotte Area Transit System (CATS) provides bus and tram service to Mecklenburg County, and its network can be seen in figure 2 to the right.

| Metrics of Adult Population who Speak Spanish  | Population  | Percentage  |
| ---------------------------------------------- | ----------- | ----------- |
| People who do not Speak English “Very Well”    | 62,537      | 58.9%       |
| People who do not Drive Alone to Work          | 34,776      | 44.1%       |
| People with Income Below Poverty Level         | 15,607      | 14.7%       |

<p class="border caption"><strong>Table 1.</strong> Metrics of the adult population of Mecklenburg County who speak Spanish. Percentages are relative to the adult population who speak Spanish.</p>

- - -

# Methods

A network analysis was performed using OpenStreetMap road and path data—excluding major roads and highways that would be infeasible or illegal to walk along—and public data on CATS routes and schedules to determine the area accessible within 45 minutes from HIV clinics with staff who speak Spanish. This was joined to US Census tracts based on the mean center of the adult population who speak Spanish but limited English, or the center of the tract if granular enough data was not available. This was compared against an overlay analysis of tracts with above county average HIV rate, population of adults in poverty who speak Spanish, and population of Spanish speakers with limited English who do not drive to work.

![Map of Transport and Poverty](/assets/images/02TransportPovertyLayout.png){: class="column float border" style="float: left; width: calc(70% - 12px); height: auto;"}
![Map of HIV Rate](/assets/images/01HIVRateLayout.png){: class="column float border" style="width: calc(30% - 12px); height: auto;"}
<span class="column float border caption" style="float: left; clear: both; width: calc(63% - 12px); height: auto;"><strong>Figure 3 (left).</strong> Dimensions of the Spanish-speaking population of Mecklenburg County are mapped by US Census tract. Blue areas have above county average population of adults in poverty who speak Spanish. Yellow areas have above county average population of Spanish speakers with limited English who do not drive to work. Purple areas have above county average populations for both metrics.</span>
<span class="column float border caption" style="width: calc(37% - 12px); height: auto;"><strong>Figure 4 (right).</strong> HIV rate per 100,000 people is mapped by ZIP code snapped to US Census tract boundaries. Gray areas have lower than county average HIV rate, and all other areas have above county average HIV rate.</span>

<hr style="clear: both;">

## References & Acknowledgements

Data pulled from [City of Charlotte and Transitland](https://www.transit.land/feeds/f-dnq-charlotteareatransitsystem), [OpenStreetMap and Geofabrik GmbH](https://download.geofabrik.de/north-america/us/north-carolina.html), [Mecklenburg County](https://maps.mecklenburgcountync.gov/openmapping/data.html), [U.S. Census and IPUMS NHGIS](https://doi.org/10.18128/D050.V20.0), [AIDSVu](https://doi.org/10.2196/23173), and the [National Prevention Information Network](https://npin.cdc.gov/search/organizations/map).

Special thanks to Dr. Lauren Kohut for her guidance on this project, to my peers in Geography 330 for all of their support, and to the workers who provide these essential services to the people of Charlotte and the surrounding areas.
