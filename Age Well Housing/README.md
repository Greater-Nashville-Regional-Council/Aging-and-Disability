# **Age Well Request**

## *Table of Contents*  
+ Overview and Sources
+ Data Prep   
+ Calculations   

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

## Calculations  

1. Population:
+ 65+ population  
2. Poverty:  
+ 56+ in poverty # and %  
3. Educational Attainment:  
+ less than 9th grade, 9th to 12th no diploma, hs graduate or equivalency, some college no degree, associates, bachelors, graduate or professional degree  
+ % of 65+ population with the above attainment levels  
4. Living Situation:  
+ 65+ population living alone # and %  
5. Grandparents:  
+ grandparents 60+ that are responsible for own grandchild no parent present  
6. Housing Burden and Tenure:  
+ cost burdened 65+ population  
+ extremely cost burdened 65+ population  
+ 65+ homeowners cost burdened and extremely cost burdened  
+ 65+ renters cost burdened and extremely cost burdened  
7. Social Security:  
+ % households with and without social security income  
8. Income:  
+ % of 65+ householder households with incomes: less than $10K, $10K-$29999, $30K-$49999, %50K-$59999, $60K - $74999, $75K to $99999, $100K+  

**Find a data guide in the files above outlining every data variable used as an input.**
