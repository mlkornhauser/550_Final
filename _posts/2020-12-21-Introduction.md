---
title: "Introduction"
date: 2020-12-22
published: true
tags: [dataviz, altair, COVID-19, SafeGraph]
excerpt: "How have businesses in major U.S. cities been impacted by stay-at-home orders during the COVID-19 pandemic?"
altair-loader:
  altair-chart-1: "charts/COVID_summary.json"
toc: true
toc_sticky: true
---

This project investigates how the first six months of the coronavirus (COVID-19) pandemic impacted businesses in top U.S. cities. By analyzing weekly foot traffic across cities from March to August 2020, I discuss the effects of government stay-at-home orders on a variety of businesses and analyzes how business traffic relates to COVID-19 infections. I work with data on the 20 largest U.S. cities, with a special focus on the following:

*	Denver, Colorado (Denver County)
*	Houston, Texas (Harris County)
*	Jacksonville, Florida (Duval County)
*	Philadelphia, Pennsylvania (Philadelphia County)
*	Phoenix, Arizona (Maricopa County)
*	San Francisco, California (San Francisco County)

## Data Used

To capture foot traffic by city, I use [SafeGraph’s Weekly Patterns] (https://docs.safegraph.com/docs/weekly-patterns), an aggregated dataset collected from mobile devices on visitor data to various places across the country. Additionally, I incorporate [SafeGraph’s Core Places dataset] (https://docs.safegraph.com/docs#section-core-places) to group the Weekly Patterns information by business type.

With regards to the COVID-19 data, I primarily used information from the [New York Times COVID-19 data repository on GitHub] (https://github.com/nytimes/covid-19-data). In particular, I look at the [COVID-19 by Counties] (https://github.com/nytimes/covid-19-data/blob/master/us-counties.csv) dataset and the [July Mask-Wearing Survey] (https://github.com/nytimes/covid-19-data/tree/master/mask-use). The county dataset compiles cumulative counts of COVID-19 cases and deaths across the country. The Mask-Wearing data reports how likely residents across the U.S. are to wear a mask. In total, the survey collected 250,000 online responses between July 2 and July 14, 2020. 

Finally, I used [city population data from Wikipedia] (https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population) and various qualitative sources to determine the dates of stay-at-home orders in each city.

## Data Cleaning & Assumptions

Because the SafeGraph data is so extensive, it was challenging to get it into a usable form. I first downloaded the weekly datasets to my local computer. I next filtered each week for the study cities and relevant variables. I then concatenated the filtered weeks into a monthly dataset and exported the monthly dataset into a new csv. 

Another challenge is that the SafeGraph provides information at the city level while the New York Times COVID-19 dataset look at the county level. For the purposes of this project, I assumed that the county-level data was representative of the relevant city’s COVID-19 infection rates.

For the stay-at-home orders, these visualizations capture when the order first went into effect and when the order expired and businesses were permitted to reopen. Additionally, not all cities mandated a stay-at-home order and relied on the state-level restrictions, as was the case for Phoenix, Arizona. In this case, the charts represent the state-level orders.

<div id="altair-chart-1"></div>
