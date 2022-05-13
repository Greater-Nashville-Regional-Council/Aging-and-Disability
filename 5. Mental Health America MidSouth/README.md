# **Mental Health America**

## *Table of Contents*  
+ Overview
+ Data Prep  
+ Calculations
+ Takeaways

## Overview  

Request received for State of Tennessee level data replicating a previous presentation given by GNRC about the GNRC region.

## Data Prep  

The following data is obtained at the state level using the Census API from the 2016-2020 American Community Survey 5-Year Estimates:  

+ B01001 population series; age by sex for the population 55+ and 65+  
+ B01001A - I population series; age by sex by race or ethnicity for the population 55+  
+ B19037 series; household income for householders age 65+  
+ variable B19049_005E; median household income for householders age 65+  
+ B25007 series; tenure for population 55+  
+ B09020 series; population 65+ living situation    
+ B10051 series; the grandparents survey  
+ B25093 series; households spending x% of their income on housing by tenure for householders 65+  
+ B05013 series; foreign-born status for the population 55+  
+ B16004 series; first language and ability to speak English for the population 65+  
+ B17001 series; poverty by age for the population 55+  


## Calculations  

1. Population age groups:  
+ Under 18  
+ 18 to 54  
+ 55 to 64  
+ 65 to 74  
+ 75 to 84  
+ 85+  
2. Race and Ethnicity:  
+ minority (not White Not Hispanic or Latino) population 55+  
+ White Not Hispanic or Latino 55+  
+ Black or African American 55+  
+ Hispanic or Latino 55+  
+ Native American, Other Alone, or Two or More Races 55+  
+ Asian or Pacific Islander 55+  
3. Household Income:  
+ Median Household Income for 65+ Householder Households  
+ 65+ Householder Households making $50,000 or less  
4. Tenure:  
+ adults 55+ who are renters  
+ homeownership rates by age groups 55-59, 60-64, 65-74, 75-84, 85+  
4. Living Situations:  
+ population 65+ living alone  
+ population 65+ living with a spouse  
5. Grandparents  
+ grandparents that are 60+  
+ of 60+ grandparents, those who are the primary caregiver for grandchild  
6. Cost Burden  
+ homeowners 65+ that are cost burdened  
+ renters 65+ that are cost burdened  
7. Foreign Born Population  
+ foreign-born population that is 55+  
8. First Language and Ability to Speak English  
+ population 65+ that has a first language besides English  
+ of this population, population that doesn't speak English "well" or "at all"  
9. Poverty  
+ population 55+ living in poverty  

## Takeaways  

Takeaways from this data pull:
+ **29.4% of the Tennessee population is age 55+**  
+ **16.4% of the Tennessee population is age 65+**  
+ **17.2% of the 55+ population in Tennessee is minority (not White Alone Not Hispanic or Latino)**  
+ **The median household income for 65+ householder households is $42,047, and 53.1% of these households have a household income less than $50,000**  
+ **19.9% of the 55+ population are renters**  
+ **the 75 to 84 population has the highest homeownership rate of all groups 55+ at 84.4%**  
+ **50.5% of grandparents are 60+, and 21.8% of these grandparents are the primary caregiver for a grandchild**  
+ **19.4% of 65+ homeowners are cost burdened, as are 47.2% of 65+ renters**  
+ **19.8% of the foreign born population is 55+**  
+ **2.6% of the 65+ population has a first language besides English, and of this group 32.2% speak English "not well" or "not at all"**  
+ **10.6% of the 55+ population is below the poverty line**
