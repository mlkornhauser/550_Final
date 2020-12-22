---
title: "Exploratory Analysis"
date: 2020-12-22
published: true
tags: [dataviz, altair, COVID-19, SafeGraph]
excerpt: "Understanding the general trends in COVID-19 cases and foot traffic across the 20 largest U.S. cities."
altair-loader:
  altair-chart-1: "charts/facet_cases.json"
  altair-chart-2: "charts/facet_deaths.json"
  altair-chart-3: "charts/COVID_Masks.json"
  altair-chart-4: "charts/foot_traffic.json"
  altair-chart-5: "charts/COVID_summary.json"
toc: true
toc_sticky: true
---

## COVID-19 cases and deaths by city

<div id="altair-chart-5"></div>

I reviewed patterns of COVID-19 cases and deaths per 10 thousand residents by city. During the first six months of the pandemic, COVID-19 impacted cities differently. New York City had a very steep curve in March mirroring the area’s early outbreak, but leveled off by the middle of the summer. Southwestern and southern counties, such as Harris County (Houston) in Texas, Maricopa Count (Phoenix) in Arizona, and Duval County (Jacksonville) in Florida, all remained relatively flat until the middle of summer when the infection rates drastically increased. 

<div id="altair-chart-1"></div>

Looking at COVID-19 deaths across the cities we see similar trends as the cases, with deaths lagging spikes in infections. Areas with earlier outbreaks appeared to suffer a higher death rate following a spike in cases, such as New York City and Cook County (Chicago) in Illinois. This is likely due to improved treatment and awareness of COVID-19 as the year progressed.

<div id="altair-chart-2"></div>

## Mask Use by City

As COVID-19 cases and deaths vary by county, so does the likelihood that residents use masks. The following chart demonstrates the likelihood of residents wearing masks by county. Midwestern and southern counties seem to have lower compliance with mask use. Notably, the data indicate that only half of residents in Marion County (Indianapolis) in Indiana always wear masks. Franklin County (Columbus) in Ohio and Duval County (Jacksonville) in Florida also have relatively low mask use. San Francisco, California has the highest rate of mask use with over three-fourths of survey respondents reporting that they always wear a mask.

<div id="altair-chart-3"></div>

## Foot Traffic by City

The below heat map shows trends in foot traffic based on how often people visit SafeGraph points of interests. Each square represents a week of total visits normalized by city population.  It is clear that foot traffic drops off in the middle of March as the pandemic started. In most cities, foot traffic resumes to a certain degree throughout the summer, though not to its pre-pandemic peak.

<div id="altair-chart-4"></div>

The above chart shows that New York  City and Los Angeles seem to have less traffic overall. I suspect that the issue is that these cities have much larger populations so the normalized value appears far lower. Another possibility is that SafeGraph has not yet identified a proportional amount of points of interest in these larger cities, which could make it challenging difficult to compare across cities.
