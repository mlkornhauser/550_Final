---
title: "Individual City Analysis"
date: 2020-12-20
published: true
tags: [dataviz, altair, COVID-19, SafeGraph]
excerpt: "Analyzing foot traffic by business type"
altair-loader:
  altair-chart-1: "charts/dash_Denver.json"
  altair-chart-2: "charts/dash_Houston.json"
  altair-chart-3: "charts/dash_Jack.json"
  altair-chart-4: "charts/dash_Philadelphia.json"
  altair-chart-5: "charts/dash_Phoenix.json"
  altair-chart-6: "charts/dash_SF.json"
toc: true
toc_sticky: true
---

## Foot Traffic & COVID-19 Cases by City

I selected six cities to conduct an in-depth review of foot traffic by business type and how this relates to COVID-19 case counts. I selected cities from different regions that demonstrated various patterns in infection rates and business traffic based on the exploratory analysis.  The six cities include:

*	Denver, Colorado
*	Houston, Texas
*	Jacksonville, Florida
*	Philadelphia, Pennsylvania
*	Phoenix, Arizona
*	San Francisco, California

For each of the six cities, I reviewed foot traffic by business type to compare how different segments of the economy was impacted by the pandemic. Due to the many business types, I narrowed down the foot traffic data to ten categories. These include:

*	Full-Service Restaurants
*	Limited-Service Restaurants
*	Supermarkets and Other Grocery (except Convenience) Stores
*	Convenience Stores
*	Fitness and Recreational Sports Centers
*	Malls
*	Gasoline Stations with Convenience Stores
*	Beer, Wine, and Liquor Stores
*	All Other General Merchandise Stores
*	Hotels (except Casino Hotels) and Motels

This analysis also shows the length of a city’s stay-at-home order with two gray lines. The solid line indicates the start of the stay-at-home order and the dotted line indicates when the reopening phase began. In addition to observing variation across stay-at-home orders, the patterns in foot traffic show where there was greater compliance with the lockdown. These charts do not account for variation among stay-at-home orders with some city’s restrictions being more stringent than others.

## Denver Colorado

Before the pandemic, we see that full-service restaurants were the main driver of foot traffic in Denver, with fitness centers, malls and limited service restaurants also reporting substantial traffic. With the start of the pandemic started in mid-March, there was a clear drop in foot traffic, even before the stay-at-home order went into effect. Foot traffic recovered somewhat after the reopening phase, but not to the pre-pandemic levels. The end of the stay-at-home order appears to coincide with a fairly consistent rise in COVID-19. While the stay-at-home order did not appear to be particularly effective at curtailing the infection rate, Denver was successful in managing COVID-19 cases for the first six months of the pandemic.

<div id="altair-chart-1"></div>

## Houston, Texas

While Houston had a longer stay-at-home order than Denver, there seemed to be less compliance with these restrictions. This lack of compliance is evidenced by the increase in foot traffic at full-service restaurants and malls well before the start of the reopening phase. Though there seemed to be inconsistent adherence to the stay-at-home order, the COVID-19 case count drastically increased at the start of the reopening phase, suggesting that the restrictions were effective.

<div id="altair-chart-2"></div>

## Jacksonville, Florida

Of the six cities, Jacksonville had both the latest and the shortest stay-at-home order. Despite the relatively short lockdown period, the below heatmap indicates that there was still ample foot traffic during the lockdown period, particularly in malls, limited-service restaurants, and general merchandise stores. Full-service restaurants did, however, experience a substantial loss of traffic.

Interestingly, the end of the short stay-at-home order did not seem to have an impact on COVID-19 cases. Jacksonville’s outbreak occurred about 6 weeks after the stay-at-home period, suggesting that the city kept its infection rate under control without these restrictions. The outbreak does appear to correlate with an increase in foot traffic at malls and restaurants and as cases continued climb throughout the summer, this traffic remained relatively constant. It is also worth noting that Jacksonville is also on the lower end of mask compliance, with only about 60% of survey respondents indicating that they always wear a mask, and nearly 10% indicating that they rarely or never wear a mask. 

<div id="altair-chart-3"></div>

## Philadelphia, Pennsylvania

Philadelphia is notable in the high share of its foot traffic related to people frequenting full-service restaurants. The rapid drop in restaurants traffic started in mid-March and continuing during the stay-at home order suggests that these restaurant restrictions may have an outsized effect on Philadelphia businesses. Customers did return to restaurants as the reopening phase began, but not only at about 50% capacity. 

<div id="altair-chart-4"></div>

## Phoenix, Arizona

Phoenix has a similar trajectory to Jacksonville, Florida where the stay-at-home period coincided with a relatively manageable COVID-19 case count. A few weeks after the start of the reopening period, however, the number of cases increases drastically.  Another interesting similarity between Phoenix and Jacksonville is the heavy traffic at malls which largely continued throughout the lockdown phase. Though it is unclear if these are indoor or outdoor malls, it suggests that people spending time in these establishments could be related to a rise in infections.

<div id="altair-chart-5"></div>

## San Francisco

Like Philadelphia, San Francisco foot traffic was largely driven by visits to full-service restaurants. Other important sectors included fitness and recreation centers, as well as hotels. While San Francisco instituted their stay-at-home order very early, before they even had reported cases, they experienced a steady rate of infection and then an uptick later in the summer about a month after the reopening phase began. As noted above, San Francisco also has the highest adoption of mask use of any study city.

<div id="altair-chart-6"></div>
