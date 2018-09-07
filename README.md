# Real-Estate-Analysis
Analysis Real Estate Trend in USA in last 10 years


## Summary 
I analyzed the Real Estate Dataset from Zillow.com. It contained data aggregated by states, Metrosand zipcodes. Datasets : Median Sale price, Price per SQFT, Inventory Day son Market datasets. Among the factors investigated were the percentage median sale price increases and pattern in the seasonality of number of houses sold during the year. 

## Insights

1. "Median Sale Price growth over years (2008 - 2018) in U.S: Median Sale price of houses in U.S increased by 55% from its rock bottom in 2011. The decrease from 2008 to 2011 can be explained by the depression in the economy and hence the housing market. But the prices seen on the y-axis, 140k - 230k, is a scale for prices unheard of in California. we see this discrepancy, due the inclusion of all states (with Housing prices high and low ranges). It could also be due the types of houses (condos, townhomes, single-family homes) and in all zipcodes.
<p align="center">
 <img src="https://github.com/SaritaIngu/Real-Estate-Analysis/blob/master/images/MediaPriceUS.png" title="Median Sale price US">
  </p>
  
2. Median Sale Price Increase By State: Michigan and Nevada had about 175% to 150% increase in Median Sale price in the last few years from Sept 2011. California came in 4th with 115% increase in meadian Sale price.
<p align="center">
  <img src="https://github.com/SaritaIngu/Real-Estate-Analysis/blob/master/images/MedianPriceIncreaseByState.png" title="Median Price Increase ByState">
</p>

3.  Median Price growth in Top Metros of Bay Area - Sept 2011 to Jun 2018: Analysis : Bay area cities a much higher percentage increase in their Median Sale price as compared to Nation increase 
           San Jose - 150%
           Santa Clara - 156%
           San Francisco - 101%
 <p align="center">
  <img src="https://github.com/SaritaIngu/Real-Estate-Analysis/blob/master/images/SF-SJC.png" title="Median Price growth in Top Metros of Bay Area">
</p>
4. Days On Market  - Seasonality through the year:  A clear pattern seasonality pattern can be observed between SF and USA over the years. Winter months (Nov - Feb) are periods of low house buying and hence the 'Days On Market' a property has been 'Active' in market are in the peak. Where as in summer properties tend to get sold faster. Hence the avg. days on market in these months is low.
<p align="center">
  <img src="https://github.com/SaritaIngu/Real-Estate-Analysis/blob/master/images/DOM%20Trend%20US%20Heatmap1.png" title="Days On Market - Heatmap">
</p>


## Data sets
Got from : https://www.zillow.com/research/data/
Sale_Counts_State:  https://github.com/SaritaIngu/Real-Estate-Analysis/blob/master/data/Home%20Sale%20Counts/Sale_Counts_State.csv

Sale Prices By Metro:  https://github.com/SaritaIngu/Real-Estate-Analysis/blob/master/data/Median%20Price/Sale_Prices_Msa.csv

Sale Prices State: https://github.com/SaritaIngu/Real-Estate-Analysis/blob/master/data/Median%20Price/Sale_Prices_State.csv

Sale Prices City: https://github.com/SaritaIngu/Real-Estate-Analysis/blob/master/data/Median%20Price/Sale_Prices_City.csv

AgeOfInventory Metro Public : https://github.com/SaritaIngu/Real-Estate-Analysis/blob/master/data/Inventory/AgeOfInventory_Metro_Public.csv

## Tools And Libraries Used
1. Jupyter Notebook
2. Seaborn, Plotly, pyplot
