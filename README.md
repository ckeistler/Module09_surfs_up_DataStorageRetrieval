# SURF'S UP ANALYSIS (Module 9)

## Overview
The premise of module 9 was based on weather analysis for a surf shop/ice cream shop in Oahu.  The challenge led us in with the following, "W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round."  We used Python, Pandas, SQLAlchemy, and Numpy to extract the needed data for analysis as below. 

## Results
![June_Data](https://user-images.githubusercontent.com/88443672/137642736-86d4b62b-ffe3-4865-8739-603bedc13c47.png)
#JUNE 
  * Avg Temp = 74.94
  * STD Temp = 3.26
  * Min Temp = 64
  * Max Temp = 85
  
![Dec_Data](https://user-images.githubusercontent.com/88443672/137642739-32f9be3f-139c-424d-b4ad-f583505bbee7.png)
#DECEMBER
  * Avg Temp = 71.04
  * STD Temp = 3.76
  * Min Temp = 56
  * Max Temp = 83
 
## Summary
![Summary](https://user-images.githubusercontent.com/88443672/137643163-8c27c4d5-86be-4385-9060-d122e331e3e5.png)
  * June's average temperature is ~3.9 degrees warmer than December's
  * December Precip/Day averaged 0.2001 vs June's .1263
  * Dec days with rain = 88/1517, or 5.8%
  * June days with rain = 39/1700, or 2.3%

In terms of temperature, December's average was 3.9 degrees colder than June, and all of the December quartiles were 3-4 degrees lower than those of June.  Precipitation occurred on 250% more days in December than in june, but overall, days with rain are quite low for both December and June (5.8% and 2.3% respectively).  The 3rd quartile for June precipitation was 0.1 vs December’s 0.13.  While Dec temps are lower than June’s, and while Dec precipitation is higher than June’s, weather conditions appear extremely favorable for outdoor activity in both months.  Our weather data does not take into account wind or swell height, which would both be extremely important in regards to a surf shop’s business outlook. 
