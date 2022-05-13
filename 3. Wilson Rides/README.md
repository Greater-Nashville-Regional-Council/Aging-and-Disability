# **Wilson Rides Request**

## *Table of Contents*  
+ Overview and Sources
+ Data Prep    

## Overview  

Request received from Wilson Rides, an organization providing services to seniors in Wilson County. This repository goes over data gathering, cleaning, and formatting.

## Data Prep  

The following data is obtained at the county level for the 13 county GNRC region using the Census API from the 2016-2020 American Community Survey 5-Year Estimates:  

+ data from the B01001 population series: age by sex
+ data from the B21001 series: veteran population by age  
+ data from the B17001 series: poverty level by age  
+ data from the B15001 series: educational attainment by age
+ data from the B09020 series: living arrangement by age  
+ data from the B25045 series: vehicle ownership by age of householder  
+ data from the B28005 series: computer ownership by internet subscription type and age  
+ data from the B25072 series: housing cost burden by age of householder  
+ data from the B07001 series: geographic mobility in the past year by age  

In the case of population age, veteran population, poverty level, and geographic mobility, data is collected for population 55+ and 65+.

Some of this information is only available for ages 65+: educational attainment, computer ownership, and housing cost burden.

Finally, grandparents responsible for grandchildren without a parent present is only available for ages 60+.  

Data prep includes summing the different groups necessary for fulfilling the request, and calculating appropriate percentages.  

**Find a data guide in the files above outlining every data variable used as an input.**
