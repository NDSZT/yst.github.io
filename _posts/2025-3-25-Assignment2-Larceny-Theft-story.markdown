---
layout: post
title: "Assignment 2: Larceny Theft Data Story"
date: 2025-03-25
categories: blog
---
# Introduction
This data story is based on the San Francisco Crime Dataset (2003-2025), which is a comprehensive record of crime incidents reported by the San Francisco Police Department (SFPD). The dataset originally covers various types of criminal activities, including assault, burglary, etc. However, my focus here is specifically on incidents categorized as **“LARCENY THEFT”**. I keep the following relevant attributes from the original dataset: Incident Date--The date when the crime was reported; Incident Time--The exact time of day the crime occurred; Incident Category--Classification of the crime type (filtered for “LARCENY THEFT” here); Police District: Geographic district within San Francisco where the incident was reported; Latitude and Longitude--Precise geographic coordinates pinpointing the location of each incident. This story aims to communicate clearly to the readers, enhancing public awareness and understanding of larceny theft.

# Visualizations and insights
**The time-bar chart of Larceny Theft.** The following bar chart shows the number of reported Larceny Theft incidents in San Francisco from **2003 to 2025**. Overall, We can see that larceny theft in San Francisco surged significantly in the **2012s**, with a dramatic peak in **2018**. Between **2003 and 2011**, the number of thefts remained relatively stable, averaging around **25,000 to 30,000 incidents** per year. After a peak in **2018**, the number of thefts dropped sharply, especially during **2019–2020**. This might be connected to **COVID--19**<a href="#ref1">[1]</a>, which drastically reduced public activity and movement, making it harder for thieves to find opportunities. While the number of larceny thefts have remained low since 2020, they were particularly low in 2024, which may be attributed to the implementation of stricter **theft-related policies** in California<a href="#ref1">[2]</a>. However, other factors may also have played a role--for example, the post-pandemic economic recovery and more stable employment conditions could have reduced some of the motivations behind larceny theft.

![My Image](https://ndszt.github.io/yst.github.io/images/larceny_theft_per_year.png)

The interactive map below displays the geographic distribution of **larceny theft incidents in San Francisco in 2018**, the peak year for this crime category. Each **orange circle** represents a cluster of theft reports in a specific area. The number inside the circle indicates how many incidents were reported in that region during the year.You can click on a circle to zoom in and see more precise locations where theft occurred, allowing for a more detailed spatial understanding of crime concentration.
It is easily to see the **highest concentration of larceny thefts (27,834 cases)** is located in the **downtown area**, including Union Square, Financial District, and Market Street (if you click the circle you will see it). In contrast, residential areas such as the Sunset District, which is farther from downtown and have lower foot traffic, experienced significantly fewer theft incidents. This pattern isn’t surprising—-larceny theft tends to happen more in busy commercial areas, tourist hotspots, and places where lots of people are moving around.

<iframe src="/yst.github.io/HTML/larceny_map_2018.html" width="100%" height="500"></iframe>

**The following chart is interactive chart of larceny theft by weekday and hour.**
<iframe src="/yst.github.io/HTML/larceny_theft_by_week.html" width="100%" height="540"></iframe>


---
### References
<span id="ref1">[1]</span> [SF.gov. *SF responds to coronavirus outbreak with Stay Home order.*](https://sf.gov/news/sf-responds-coronavirus-outbreak-stay-home-order) Published March 20, 2020.\\
<span id="ref1">[2]</span> [Office of Governor Gavin Newsom. *Governor Newsom signs landmark legislative package cracking down on retail crime and property theft.*](https://www.gov.ca.gov/2024/08/16/governor-newsom-signs-landmark-legislative-package-cracking-down-on-retail-crime-and-property-theft/) Published August 16, 2024.
