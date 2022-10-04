## Friday, September 16th, 2022
### - Went through OurWorldinData chart and available data and realized that all available variables are aggregates and decided to use another data source from MeteoStat (via RapidAPI)
### - Spent time trying to acquire Daily data from API, currently 
### Issue(s): followed instructions and acquired API key to retrieve data yet still getting error: "You are not subscribed to this API" despite acquiring basic subscription in RapidAPI


### Friday, September 23rd 2022
### explored another datasource for ice glacier data 
### I want to implement an LSTM for anomaly detection and I realized that it would not make sense to apply this method to such data. (ice melting, progressively decreasing). I'm thinking if any anomalies are detected it would probably input/reporting errors if anything, but I could be wrong. 

### October 4th 2022
### Started working with the previous meteostat data again. Still findig the best method of reading it in/using it. I read through data documentation. My variables of interest are snow depth, wind speed, average sea-level pressure, average air temperature, and daily precipitation.
### tried out reading in data using the meteostat library (I was unaware of this before :'()
### tested out creating a time series plot for vancouver, bc that was found in documentation. 



