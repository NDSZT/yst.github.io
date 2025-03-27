---
layout: post
title: "Assignment 2: Larceny Theft Data Story"
date: 2025-03-25
categories: blog
---
# Introduction
This data story is based on the San Francisco Crime Dataset (2003-2025), which is a comprehensive record of crime incidents reported by the San Francisco Police Department (SFPD). The dataset originally covers various types of criminal activities, including assault, burglary, etc. However, my focus here is specifically on incidents categorized as **“LARCENY THEFT”**. I keep the following relevant attributes from the original dataset: Incident Date--The date when the crime was reported; Incident Time--The exact time of day the crime occurred; Incident Category--Classification of the crime type (filtered for “LARCENY THEFT” here); Police District: Geographic district within San Francisco where the incident was reported; Latitude and Longitude--Precise geographic coordinates pinpointing the location of each incident. This story aims to communicate clearly to the readers, enhancing public awareness and understanding of larceny theft.

# Visualizations and insights
**The time-bar chart of Larceny Theft.** The following bar chart shows the number of reported Larceny Theft incidents in San Francisco from **2003 to 2025**. Between **2003 and 2011**, the number of thefts remained relatively stable, averaging around **25,000 to 30,000 incidents** per year. After a peak in **2018**, the number of thefts dropped sharply, especially during **2019--2020**. This might be connected to **COVID-19**<a href="#ref1">[1]</a>, which drastically reduced public activity and movement, making it harder for thieves to find opportunities. While the number of larceny thefts have remained low since 2020, they were particularly low in 2024, which may be attributed to the implementation of stricter **theft-related policies** in California<a href="#ref1">[2]</a>. However, other factors may also have played a role--for example, the post-pandemic economic recovery and more stable employment conditions could have reduced some of the motivations behind larceny theft. Overall, We can see that larceny theft in San Francisco surged significantly in the **2012s**, with a dramatic peak in **2018**. And this sudden surge in 2018 raised the question: where exactly were these thefts happening across the city? To answer that, I visualized the spatial distribution on a map.

![My Image](https://ndszt.github.io/yst.github.io/images/larceny_theft_per_year.png)

The interactive map below displays the geographic distribution of **larceny theft incidents in San Francisco in 2018**, the peak year for this crime category. Each **orange circle** represents a cluster of theft reports in a specific area. The number inside the circle indicates how many incidents were reported in that region during the year.You can click on a circle to zoom in and see more precise locations where theft occurred, allowing for a more detailed spatial understanding of crime concentration.


It is easily to see the **highest concentration of larceny thefts (27,834 cases)** is located in the **downtown area**, including Union Square, Financial District, and Market Street (if you click the circle you will see it). In contrast, residential areas such as the Sunset District, which is farther from downtown and have lower foot traffic, experienced significantly fewer theft incidents. This pattern isn’t surprising--larceny theft tends to happen more in busy commercial areas, tourist hotspots, and places where lots of people are moving around (not just in 2018). Of course, crime isn’t just about where—it’s also about when. So I dug deeper to see how thefts change throughout the day and across different weekdays.

<iframe src="/yst.github.io/HTML/larceny_map_2018.html" width="100%" height="500"></iframe>

The following interactive chart shows **how larceny theft incidents vary by hour across different days of the week**. You can click the buttons at the top (Monday to Sunday) to view or hide each day's line. The line color fades from dark to light, corresponding to Monday (darkest) through Sunday (lightest)--making it easy to compare weekday patterns. And when you hover your mouse over a data point, it will displays detailed information--including the hour and the number of incidents.


From the chart, we can observe that the overall trend is quite consistent across all weekdays. In every case, the number of larceny theft incidents is lowest between **2 AM and 6 AM**--which is expected, as there are fewer people out during those early morning hours. Theft activity typically starts to rise later in the morning, peaks around **6 PM**, and then gradually declines as the night progresses. However, there’s a noticeable exception on Friday and Saturday nights, where theft incidents slightly increase again after **9 PM**, and even remain relatively high around midnight. This could be because people tend to stay out later on weekends--especially in areas where theft is more common, such as nightlife districts or commercial zones. Interestingly, the total number of theft incidents appears to be slightly lower on weekends compared to weekdays. This might be due to fewer active businesses and commuters in commercial areas, reducing the number of potential targets. In addition, increased police presence and heightened awareness during weekend nightlife hours may also contribute to fewer reported cases overall<a href="#ref1">[3]</a>.

<iframe src="/yst.github.io/HTML/larceny_theft_by_week.html" width="100%" height="540"></iframe>

# Conclusion
Working on this data story helped me understand not just the numbers behind larceny theft in San Francisco, but also the broader patterns shaping when and where it happens. The sharp rise in thefts leading up to 2018--and the dramatic drop during the pandemic--highlight how much external factors like public health, movement restrictions, and economic conditions can influence crime rates. I was also struck by how concentrated thefts are in the downtown area, especially near Market Street and Union Square. It makes sense--these are busy, high-traffic zones where opportunities for theft are more common, which prove the role of environment in crime patterns.The hourly and weekday breakdowns were especially interesting. Theft activity follows a pretty consistent rhythm across the week, peaking in the late afternoon and early evening. But I didn’t expect the subtle rise late on Friday and Saturday nights—that detail made me think about how nightlife and weekend behavior might influence larceny theft.


Overall, this story made me see crime data not just as statistics, but as reflections of human activity, habits, and the way cities work. Hopefully, these insights can help others better understand how and why larceny theft happens--and maybe even how to prevent it.


---
### References
<span id="ref1">[1]</span> [SF.gov. *SF responds to coronavirus outbreak with Stay Home order.*](https://sf.gov/news/sf-responds-coronavirus-outbreak-stay-home-order) Published March 20, 2020.\\
<span id="ref1">[2]</span> [Office of Governor Gavin Newsom. *Governor Newsom signs landmark legislative package cracking down on retail crime and property theft.*](https://www.gov.ca.gov/2024/08/16/governor-newsom-signs-landmark-legislative-package-cracking-down-on-retail-crime-and-property-theft/) Published August 16, 2024.\\
<span id="ref1">[3]</span> San Francisco Police Department. *SFPD Arrests 61 Organized Retail Crime Suspects in Recent Blitz Operations.* [https://www.sanfranciscopolice.org/news/sfpd-arrests-61-organized-retail-crime-suspects-recent-blitz](https://www.sanfranciscopolice.org/news/sfpd-arrests-61-organized-retail-crime-suspects-recent-blitz). Published March 25, 2025.
