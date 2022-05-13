# **Senior Veteran Population**

## *Table of Contents*  
+ Overview
+ Data Prep  
+ Results    

## Overview  

MySidewalk does not have veteran status by age, and this is requested as a demographic overview for the GNRC Senior Center profiles.  

## Data Prep  

The following data is obtained at the county level for the 13 county GNRC region using the Census API from the 2016-2020 American Community Survey 5-Year Estimates:  

+ data from the B21001 population series; age by sex by veteran status  

There is a data limitation where veteran population by age is not able to be determined for the entire region for ages 60+ (this was the original ask). The ACS Subject Tables have series S0102 that does collect this data, however it is not available for less populous counties including Stewart, Humphreys, Houston, and Trousdale.

For this reason, data is collected for the 65+ population to match the rest of the profile data.

Data prep includes calculating the total population 65+ for this data series, the # of veterans 65+, the percent of veterans who are seniors, and the percent of the senior population who are veterans.  

## Results  

The table containing this data for each county and the 13 county region is found below:  

![2020 Table](/images/2020_table.PNG)

**This data is exported to be imported as original data in MySidewalk.**
