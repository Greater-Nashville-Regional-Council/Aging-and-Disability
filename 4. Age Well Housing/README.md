# **Age Well Request**

## *Table of Contents*  
+ Overview and Sources
+ Data Prep    

## Overview  

Request received from Age Well Tennessee. Request for data demonstrating the need for affordable housing for seniors in the Middle Tennessee 14-county region (GNRC region + Maury County).

## Data Prep  

The following data is obtained at the county level for the 14 county GNRC region using the Census API from the 2016-2020 American Community Survey 5-Year Estimates:  

+ data from the B01001 population series: age by sex
+ data from the B17001 series: poverty level by age  
+ data from the B15001 series: educational attainment by age
+ data from the B09020 series: living arrangement (alone) by age  
+ data from the B25072 series: housing cost burden by age of householder  
+ data from the B19055 series: households with social security income  
+ data from the B19037 series: household income for householders 65+  
+ data from the B25007 series: tenure by householder age  

Grandparents responsible for grandchildren without a parent present is only available for ages 60+, the rest of this data represents seniors age 65+.

Data prep includes summing the different groups necessary for fulfilling the request, and calculating appropriate percentages.  

**Find a data guide in the files above outlining every data variable used as an input.**
