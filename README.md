# Toronto Road Collisons factor analysis? <img align="right" alt="Coding" width="180" src="https://i.giphy.com/media/VhWFMl9M6zKpqB2dkc/giphy.webp">
 > Group Project for [SAS - 2022 Safe Roads Competition](https://www.sas.com/en_ca/events/2021/q4/safe-roads-competition.html) in partnership with Geotab Inc. and the Toronto Police Services.
 
 > Access the Presentation 👉🏼 [Here](https://github.com/AlkaBhambhu/Safe-Roads-Competition/blob/124b69d75fc6c9ed745e8f22cde23cef08724a5f/2022%20Safe%20Roads%20Competition%20Final%20Version.pdf)

## Overview 
> "The main objective of this case is to understand the factors that affect traffic safety utilizing the datasets provided by Geotab, the Toronto Police Service, and other open data sources.The aim of the project is to extract insights from the data and provide specific recommendations to improve traffic safety in your municipality."

-2022 SAS Safe Roads Case Document

    How might we reduce the occurence of collisions in Toronto? 

## Point of Inquiry 

Which factors drive the occurence of collisions:
- Driver related
- Pedestrian related
- Environment related
- Are factors same for Downtown & Non-Downtown region?

## Tools used
1. Linear Regression - To identify Behavioural & Environmental Factors
2. K-mode Clustering - To group Driver's behaviour and create personas
3. Decision Tree - To identify Behavioural & Environmental Factors
4. Random Forest - To determine feature importance

## Results 
- Visualisation of Traffic improvement measures and incidents occurence on the map of Toronto identified hotspots and a blindspot (in the Northeastern region).
- Factors like intersections, average acceleration, visibility and volume of vehicles came up as significant variables in models, confirming the past studies.
- In pedestrian related factors, pedestrian inattentiveness showed up as a primary cause, much more so than other variables like pedestrain impairment.Another major factor is 'crossing streets where there is no traffic control'
- Factors for:
  - Downtown: Heavy traffic flow combined with inattentiveness leads to greater collisions. Also, most collisions occur during the night.
  - Non-Downtown: Weather & road surface conditions combined with speeding leads to greater collisions. Also, most collisions occur during the day.

## Limitation
We identified the lack of a full set of causal factors in the dataset. The dataset doesn’t include the effect of construction, and other road congestion issues on traffic incidents. A more comprehensive analysis combining more datasets would lead to a more complete analysis. 

