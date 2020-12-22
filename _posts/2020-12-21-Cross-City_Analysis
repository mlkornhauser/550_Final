---
title: "Exploratory Analysis"
date: 2020-12-20
published: true
tags: [dataviz, altair, COVID-19, SafeGraph]
excerpt: "COVID-19 cases and foot traffic across the largest 20 U.S. cities."
altair-loader:
  altair-chart-1: "charts/facet_cases.json"
  altair-chart-2: "charts/facet_deaths.json"
  altair-chart-3: "charts/COVID_Masks.json"
  altair-chart-4: "charts/foot_traffic.json"
toc: true
toc_sticky: true
---
## COVID-19 cases and deaths by city

I reviewed patterns of COVID-19 cases and deaths per 10 thousand residents by city.  A few notable cities stand out.  New York City had a very steep curve at the beginning of the pandemic mirroring the area’s early outbreak, but levels off by the middle of the summer. Southwestern and southern counties, such as Harris County (Houston) in Texas, Maricopa Count (Phoenix) in Arizona, and Duval County (Jacksonville) in Florida, all remained relatively flat until the middle of summer when the infection rates drastically increased. 

<div id="altair-chart-1"></div>

Looking at COVID-19 deaths across the cities we see similar trends as the cases, with deaths lagging spikes in infections. For areas with earlier outbreaks, such as New York City and Cook County (Chicago) in Illinois, there appears to be a higher death rate following an outbreak. This is likely due to larger awareness of the disease as healthcare professionals improving their treatment.

<div id="altair-chart-2"></div>

## Mask Use by City

As COVID-19 counts vary by county, so do mask rates. The following chart demonstrates the likelihood of residents wearing masks by county. Midwestern and southern counties seem to have lower compliance with mask use. Notably, the data indicate that only half of residents in Marion County (Indianapolis) in Indiana always wear masks. Franklin County (Columbus) in Ohio  and Duval County (Jacksonville) in Florida also have relatively low mask use. San Francisco, California has the highest rate of mask use with over three-fourths of survey respondents reporting that they always wear a mask.

<div id="altair-chart-3"></div>

## Foot Traffic by City

The below heat map shows trends in foot traffic based on how often people visit SafeGraph points of interests. Each square represents a week of total visits normalized by city population.  It is clear that foot traffic drops off in the middle of March as the pandemic started. In most cities, foot traffic resumes to a certain degree throughout the summer, though not to its pre-pandemic peak.

<div id="altair-chart-4"></div>

The above chart shows that New York  City and Los Angeles seem to have less traffic overall. I suspect that the issue is that these cities have much larger populations so the normalized value appears far lower. Another possibility is that SafeGraph has not yet identified a proportional amount of POIs in these larger cities, which could make it challenging difficult to compare across cities.
