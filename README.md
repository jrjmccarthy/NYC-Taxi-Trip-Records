# NYC Taxi Trip Records Project

This repository contains data processing and analysis code for New York City yellow taxi trip records during the month of January 2025. The goals of the analysis are trifold. First, I will compare descriptive statistics on congestion fee revenue, trip duration, and the number of taxi trips entering lower Manhattan before and after the implementation of the MTA Congestion Relief Zone on January 5th, 2025. Second, I will analyze the spatial distribution of demand to understand where yellow taxis are being used. Lastly, I will model the effects of distance, rush hour, and trips located in Manhattan on yellow taxi trip duration.

## Raw Data

I used the January 2025 yellow taxi trip record parquet file, taxi zone lookup table, and taxi zone shapefile, all of which can be found on the [TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) website. Additionally, I found the trip record user guide and yellow trips data dictionary files also found at the above link useful. 

## Files

* McCarthy NYC TLC Data Project.ipnyb: loads, processes, validates, and analyzes the yellow taxi trip record data. 
