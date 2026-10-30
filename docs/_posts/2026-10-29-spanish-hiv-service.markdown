---
layout: post
title:  "Public Transit Access to Spanish-Language HIV Services"
date:   2026-10-29 20:41:17 -0400
categories: jekyll update
---

<style>
  table {
    margin: 0px;
    margin-bottom: 4px;
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

![Map of Need and Access](/assets/images/NeedAccessLayout.png){: class="border"}
<span class="border caption" style="display: block; margin-top: 4px;"><strong>Figure 1.</strong> Access and need levels are mapped by US Census tract. Of particular note are the magenta areas, representing tracts with high need for public transit access to Spanish-language HIV services—defined as areas with above county average HIV rate, population of adults in poverty who speak Spanish, and population of Spanish speakers with limited English who do not drive to work—but low access to these services—defined as being more than 45 minutes by walking and public transit from an HIV clinic with staff who speak Spanish. Map by Emberlynn McKinney.</span>

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

![Map of Transport and Poverty](/assets/images/02TransportPovertyLayout.png){: class="column float border" style="float: left; width: 67%;"}
![Map of HIV Rate](/assets/images/01HIVRateLayout.png){: class="column float border" style="width: 28%;"}
<span class="column float border caption" style="float: left; clear: both; width: 60%;"><strong>Figure 3 (left).</strong> Dimensions of the Spanish-speaking population of Mecklenburg County are mapped by US Census tract. Blue areas have above county average population of adults in poverty who speak Spanish. Yellow areas have above county average population of Spanish speakers with limited English who do not drive to work. Purple areas have above county average populations for both metrics. Map by Emberlynn McKinney.</span>
<span class="column float border caption" style="width: 35%;"><strong>Figure 4 (right).</strong> HIV rate per 100,000 people is mapped by ZIP code snapped to US Census tract boundaries. Gray areas have lower than county average HIV rate, and all other areas have above county average HIV rate. Map by Emberlynn McKinney.</span>

<hr style="clear: both;">

## References & Acknowledgements

City of Charlotte. 2026. “GTFS Feed: Charlotte Area Transit System (CATS).” Charlotte Area Transit System. GTFS. Transitland. <https://www.transit.land/feeds/f-dnq-charlotteareatransitsystem>.

Geofabrik GmbH. 2026. “OpenStreetMap for North Carolina.” OpenStreetMap, February 25. OSM PBF. Geofabrik Download Server. <https://download.geofabrik.de/north-america/us/north-carolina.html>.

Mecklenburg County. 1999. “County Boundary.” Open Mapping, March 31. Shapefile. <https://maps.mecklenburgcountync.gov/openmapping/data.html>.

Schroeder, Jonathan, David Van Riper, Steven Manson, et al. 2025. “IPUMS National Historical Geographic Information System: Version 20.0.” IPUMS. <https://doi.org/10.18128/D050.V20.0>.

Sullivan, Patrick Sean, Cory Woodyatt, Chelsea Koski, et al. 2020. “A Data Visualization and Dissemination Resource to Support HIV Prevention and Care at the Local Level: Analysis and Uses of the AIDSVu Public Data Resource.” Journal of Medical Internet Research 22 (10): e23173. <https://doi.org/10.2196/23173>.

United States CDC. n.d. “Organization Search.” National Prevention Information Network. CSV. Accessed February 17, 2026. <https://npin.cdc.gov/search/organizations/map>.

Special thanks to Dr. Lauren Kohut for her guidance on this project, to my peers in Geography 330 for all of their support, and to the workers who provide these essential services to the people of Charlotte and the surrounding areas.