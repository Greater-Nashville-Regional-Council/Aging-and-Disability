# **Wilson Rides Request**

## *Table of Contents*  
+ Overview and Sources
+ Data Prep  
+ Calculations    

## Overview  

Request received from Wilson Rides, an organization providing services to seniors in Wilson County. This repository goes over data gathering, cleaning, and formatting.

## Data Prep  

The following data is obtained at the county level for the 13 county GNRC region using the Census API from the 2016-2020 American Community Survey 5-Year Estimates:  

+ B01001 population series: age by sex
+ B21001 series: veteran population by age
+ B17001 series: poverty level by age  
+ B15001 series: educational attainment by age
+ B09020 series: living arrangement by age  
+ B25045 series: vehicle ownership by age of householder  
+ B28005 series: computer ownership by internet subscription type and age  
+ B25072 series: housing cost burden by age of householder  
+ B07001 series: geographic mobility in the past year by age  

In the case of population age, veteran population, poverty level, and geographic mobility, data is collected for population 55+ and 65+.

Some of this information is only available for ages 65+: educational attainment, computer ownership, and housing cost burden.

Finally, grandparents responsible for grandchildren without a parent present is only available for ages 60+.  

## Calculations  

1. Age by sex:  
+ '# and % 55+  
+ # and % 65+  
2. Veteran status:  
+ # veterans 55+  
+ # veterans 65+  
+ % of all veterans that are 55+  
+ % of all veterans that are 65+  
3. Poverty:  
+ # in poverty 55+ and 65+  
+ % of below poverty level population that is 55 and 65+  
+ % of 55 and 65+ population below poverty level  
4. Educational Attainment:  
+ # less than 9th grade, 9th to 12th no diploma, hs graduate or equivalency, some college no degree, associates, bachelors, graduate or professional degree  
+ % of 65+ population with the above attainment levels  
5. Living Situation:  
+ # and % of 65+ population living alone  
6. Vehicle Ownership:  
+ # of households with 65+ householders with no vehicle  
7. Grandparents:  
+ # of grandparents 60+ that are responsible for own grandchild no parent present  
8. Computers:  
+ # of 65+ population with a computer  
+ # 65+ population with a computer with only dialup  
+ # 65+ population with a computer with broadband  
+ # 65+ population with a computer with no internet  
+ # 65+ population without a computer  
9. Housing Burden and Tenure:  
+ # cost burdened 65+ population  
+ # extremely cost burdened 65+ population  
+ # of 65+ homeowners cost burdened and extremely cost burdened  
+ # of 65+ renters cost burdened and extremely cost burdened  
+ renters 65+  
+ homeowners 65+
10. Geographic Mobility within the Past Year  
+ # and % 55 and 65+: no move same house, moved same county, moved counties same state, moved states, or moved from abroad

Data prep includes summing the different groups necessary for fulfilling the request, and calculating appropriate percentages.  

**Find a data guide in the files above outlining every data variable used as an input.**
