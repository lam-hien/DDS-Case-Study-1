# DDS-Case-Study-01  
Author: Hien Lam    
Date: 10/23/2021    
Abstract: MSDS6306: Doing Data Science - Case Study 01: Beer & Brewery. I cleaned the data and performed EDA to view distribution (log transformed when necessary) and relevant summary statistics. I conducted various hypothesis tests, k-NN cross validation on normalized values, linear regression model, and correlation tests to derive r, its p-value, r squared. Lastly, I examined the geographical distribution of IBU in order to recommend appropriate beer attributes that cater to the unmet needs of the regional markets.

## Contents of repository

1. Datasets: Beer & brewery csv files  
2. Codes: RMD, knitted html
3. Presentation: PDF of powerpoint, plotly of IBU distribution by cities

## Summary of findings
- ABV and IBU distribution both have right skew distribution.
- ABV and IBU are linearly correlated  
- Ale and IPA styles have different median ABV and IBU values
- k-NN cross validation model has 78% accuracy, 83% sensitivity, 70% specificity.
- Number of breweries per city and maximum IBU are linearly correlated.
- Boston has an unmet market for higher IBU beer production

## Conclusion
There are 558 total breweries in the United States encompassing all 50 states plus Washington DC. Colorado has the most breweries at 47. For the least at one brewery, there is a four-way tie: North Dakota, South Dakota, West Virginia, and Washington DC. ABV and IBU each have right skewness with outliers so the median is a better indicator of the distribution. ABV and IBU has strong positive, linear relationship. Ale beer is associated with lower values of ABV and IBU while IPA beer leans toward higher values of ABV and IBU. There is strong evidence to suggest the median ABV and IBU value for both ale and IPA styles are different. 
Portland has the highest number of breweries with 39 and its max IBU is 103. Similarly, SD has the third highest number of breweries with 35 and its max IBU is 115. I’ve only given you two examples, but there is a strong linear correlation between breweries per city and its maximum IBU. Additionally, it is estimated that 63% of the variation in max IBU is explained by its linear relationship with breweries per city. This leads me to infer cities with a high number of breweries have a more developed palate for crafty beers that have high IBU. Why is this important? Boston is ranked 12th in breweries per city yet its maximum IBU is only 45. That’s 50% less than the max IBU compared to cities with similar demographics. In fact, if you take the max IBU of all the cities in MA and extract the median, Boston is still 30 IBU lower. I believe that Boston is an untapped market with a need for higher IBU beer production.
