# Surfs Up Analysis

## Overview

Investing in new businesses can be tricky, but it can also be extremely rewarding if the investment pays off. An investor is considering investing in ‘Waves and Ice Cream’. This shop would serve surf boards and ice cream to locals and tourists alike in Oahu, Hawaii. This analysis is to create a weather dataset from Oahu, Hawaii to determine whether opening this business would be a viable option. 

### Resources Utilized to Complete Analysis
* **Data Sources:** 
[hawaii.sqlite](https://github.com/RabidZippers/Surfs_Up/blob/main/hawaii.sqlite)

* **Languages:** Python
* **Applications:** SQLite, SQLAlchemy
* **Tools:** Pandas, Jupyter Notebook

## Results
This analysis sampled data from different months of the year, to determine if there were big variations in the results. Specifically, the temperature data was sampled for the months of June and December in Oahu, Hawaii, to determine if the surf and ice cream shop business would be sustainable year-round.

By utilizing Python, Pandas, and SQLAlchemy, a database was created in order to retrieve all the temperatures for the months of June and December. The data obtained, provided a summary statistics were generated. 

### Summary Statistics: June vs. December Temperature
A total of 9 weather stations captured data. For the months of June and December, various statistics were captured pertaining to the temperature. 

![June_Temperature](https://github.com/cmmgw/Surfs_Up/blob/main/Resources/June_Temperature.PNG)

![December_Temperature](https://github.com/cmmgw/Surfs_Up/blob/main/Resources/December_Temperature.PNG)

The results indicate key differences in weather between June and December. 
* There are more data points capturing temperature in June versus December. 
* The lowest temperature is marked with an 8-degree difference (June: 64F, December: 56F), but the high temperature is marked with a 2-degree difference (June: 85F, December: 83F). 
* The average temperature in June is 74.9 and in December is 71.0, showing little variance.

## Summary
Given Oahu, Hawaii’s geographic location, it only has two seasons, summer and winter. 

A histogram was created to plot the underlying frequency distribution of the various temperature observations, throughout the year, at the most active weather station. Temperatures ranging from 75F – 77F occurred the most often. The findings are consistent with the results from above.

![Temperature_vs_Frequency](https://github.com/cmmgw/Surfs_Up/blob/main/Resources/Temperature_vs_Frequency.png)


Although there are evident temperature variations between the seasons, it would be helpful to further examine the data to evaluate how elevation and trade winds contribute to temperature fluctuations. In addition, further analysis can be done on tropical storm patterns. An initial look at precipitation patterns can be seen below. 

![June_Precipitation](https://github.com/cmmgw/Surfs_Up/blob/main/Resources/June_Precipitation.PNG)

![December_Precipitation](https://github.com/cmmgw/Surfs_Up/blob/main/Resources/December_Precipitation.PNG)

This further analysis is necessary to determine whether “Waves and Ice Cream” should be open year-round.
