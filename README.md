# The Impact of New River Gorge Becoming a National Park

## Table of Contents
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normaling-the-data)
* [Problems and Challenges](#problems-and-challenges)
* [Technologies Used](#technologies-used)
* [Sources](#sources)

## Motivation:
= West Virginia, a hidden gem nestled in the Appalachian Mountains, often gets overlooked. By analyzing visitation data, we can assess the impact of the New River Gorge National Park designation on attracting visitors—many of whom may be experiencing West Virginia for the first time. This analysis will not only highlight the state's growing appeal, but also demonstrate that West Virginia is evolving in ways that may surprise many. By forecasting future visitation growth, we can inspire others to explore and appreciate the beauty of this state for years to come.

## Questions:
1) How did designation impact visitation trends? How does visitation numbers look specifically in 2019-2020 compared to other State Parks? After finding this, are we able to determine if the designation played a crucial role in visitation increase?

2) Did the designation have an impact on the number of nights people were staying at the park? Did numbers increase, decrease or stay the same? Could anything else have affected the increase, decrease or stay the same?

3) How does the New River Gorge’s visitation numbers compare to all other National Parks in the year of 2024? Is there a collective upward trend or is New River Gorge seeing higher visitation numbers? What could be the cause of the result?

4) How does the impact of a designation of a Historic National Park compare to the designation of a National Park? Are visitation numbers similar? How did visitation look from 2019-2020 at Historic National Parks? What could the cause of the similarity or difference be?

## Acquiring and Normalizing the Data
- I found all of the data on nps.org. I originally planned to have a larger data set but some of the data had been removed from the website.

For normalization, I had to normalize when comparing the West Coast to the East Coast because the West Coast experiences a larger volume of visitation and has longer established National Parks.

## Problems and Challenges 
1) Downloading the Data: When I initally downloaded the data, the column headers did not download with it so I had to go and verify that the numbers matched correctly for each dataset. 

2) Changing the Data Type: All the numbers existed as strings so they all had to be converted to integers for me to perform any calculations.

3) The Size of the Data Set: This was a large dataset, I started by trying to do a comparison of all the National Parks but the graphs had too many aspects to be understood. Then I narrowed it down to East Coast and West Coast, and the data set was still overwhelming. I finally landed on finding National Parks that had similar offerings as the New River Gorge to use as my comparison, which narrowed the data set down to digestable and impactful insights. 



## Technologies Used
1) Python: I used a Jupyter Notebook to perform my analysis because it was what I was most comfortable with manipulating. It also allowed me to perform the equations I wanted to in order to predict future visitation.

2) Folium: This is how I created my interactive visitation map to show the increase of visitation from 2017-2030.

3) Canva: This is what I used to create my presentation on.

2) Github: I used this to host my shareable link and all of my documentation.

## Data Sources

1) NPS Stats: https://irma.nps.gov/Stats/Reports/National

2) NPS Stats by Region: https://irma.nps.gov/Stats/SSRSReports/National%20Reports/Annual%20Visitation%20by%20Park%20Type%20or%20Region%20(1979%20-%20Last%20Calendar%20Year)