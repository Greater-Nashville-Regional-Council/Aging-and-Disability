# **Senior Minority Population**

## *Table of Contents*  
+ Overview
+ Data Prep
+ Calculations   
+ Takeaways
+ Maps  

## Overview  

Request received for total population, total minority population, 60+ population, and 60+ minority population.  

## Data Prep  

The following data is obtained at the county level for the 13 county GNRC region using the Census API from the 2016-2020 American Community Survey 5-Year Estimates:  

+ B01001 series; age by sex
+ B01001H series; age by sex

There is a data limitation where minority population in terms of both race and ethnicity is not able to be determined for the entire region for ages 60+ (this was the original ask). The ACS Subject Tables have series S0102 that does collect this data, however it is not available for less populous counties including Stewart, Humphreys, Houston, and Trousdale. For this reason, data is collected at 55+ and 65+.

## Calculations  

1. Population age groups:  
+ 55+ population  
+ 65+ population  
2. Minority population:  
+ Non-White Alone not Hispanic or Latino population 55+  
+ Non-White Alone not Hispanic or Latino population 65+  

## Takeaways

In the GNRC Region:
+ **The total population is 1,996,337, and of that the total minority population is 598,698 (29.99% of the total population).**
+ **There are 491,717 people total over 55, and 254,676 total people over 65.**
+ **There are 94,803 minorities over age 55 (19.28% of age group), and 41,584 minorities over age 65 (16.33% of age group)**

## Maps

This data can be further explored with an interactive geospatial visualization.
Find choropleth maps of the total minority population, over 55 minority population, and over 65 minority population <a href="https://nbviewer.org/github/Greater-Nashville-Regional-Council/Aging-and-Disability/blob/main/1.%20Senior%20Minority%20Population/notebooks/2.%20Maps.ipynb">here</a>. Scroll down to see and interact with the three maps.
