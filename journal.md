### Friday, September 16th, 2022
** Went through OurWorldinData chart and available data and realized that all available variables are aggregates and decided to use another data source from MeteoStat (via RapidAPI)
** Spent time trying to acquire Daily data from API, currently 
** Issue(s): followed instructions and acquired API key to retrieve data yet still getting error: "You are not subscribed to this API" despite acquiring basic subscription in RapidAPI


### Friday, September 23rd 2022
** explored another datasource for ice glacier data 
** I want to implement an LSTM for anomaly detection and I realized that it would not make sense to apply this method to such data. (ice melting, progressively decreasing). I'm thinking if any anomalies are detected it would probably input/reporting errors if anything, but I could be wrong. 

### October 4th 2022
** Started working with the previous meteostat data again. Still finding the best method of reading it in/using it. I read through data documentation. My variables of interest are snow depth, wind speed, average sea-level pressure, average air temperature, and daily precipitation.
** tried out reading in data using the meteostat library (I was unaware of this before :'()
** tested out creating a time series plot for vancouver, bc that was found in documentation. 

### October 11th, 2022
** Considered working with another dataset: household_power_consumption.txt or sunspot data. 

### October 18th, 2022 
** started data cleaning removed tsun var column (daily sunshine total in minutes) since data is not recorded
** examined distributions of variables (histograms) to see overall shape of data. 
** Read over several articles to review best practices to handle missing data across multiple variables. Considering between removing data entirely or interpolating missing data using Hist Gradient Boosting Regressor since it has native support for missing values NaNs. 

** testing testing (getting errors when trying to push to main)

### October 24th, 2022
** conducted correlation analysis and retained tavg (avg temperature variable) to avoid redunancy in data. 

### November 10th, 2022
** started building out first iteration of model 

### December 6th, 2022
** decided to change project direction entirely. Decided to look for Earthquake data for the Caribbean to possible conduct anomaly detection methods for earthquakes above a certain magnitude. 

### December 7th, 2022
** decided to go through USGS earthquake dataset
** curious about whether magnitude or depth could be predicted based on location and other variables. 

### December 15th, 2022
** final commit, and paper submission