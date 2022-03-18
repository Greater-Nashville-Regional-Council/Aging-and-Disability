# **Senior-Minority-Population**

## *Table of Contents*  
+ Overview
+ Data Prep  
+ Results  
+ Maps  

## Overview  

Request received for total population, total minority population, 60+ population, and 60+ minority population.  

## Data Prep  

The following data is obtained at the county level for the 13 county GNRC region using the Census API from the 2016-2020 American Community Survey 5-Year Estimates:  

+ data from the B01001 population series; age by sex for the population 55+ and 65+  
+ data from the B01001H population series; age by sex for the White Alone, Non Hispanic or Latino Population 55+ and 65+  

There is a data limitation where minority population in terms of both race and ethnicity is not able to be determined for the entire region for ages 60+ (this was the original ask). The ACS Subject Tables have series S0102 that does collect this data, however it is not available for less populous counties including Stewart, Humphreys, Houston, and Trousdale.

For this reason, data is collected  at 55+ and 65+.

Data prep includes summing the different groups necessary for fulfilling the requests, and formatting groupby statements in order to get the final results.  

## Results  

In the GNRC Region:
+ **The total population is 1,996,337, and of that the total minority population is 598,698 (29.99% of the total population).**
+ **There are 491,717 people total over 55, and 254,676 total people over 65.**
+ **There are 94,803 minorities over age 55 (19.28% of age group), and 41,584 minorities over age 65 (16.33% of age group)**

## Maps

This data can be further explored with an interactive geospatial visualization.
Find choropleth maps of the total minority population, over 55 minority population, and over 65 minority population <a href="https://nbviewer.org/github/Greater-Nashville-Regional-Council/Aging-and-Disability/blob/main/Senior%20Minority%20Population/notebooks/2.%20Maps.ipynb">here</a>. Scroll down to see and interact with the three maps.
