## Estimating Excess Deaths
### Forecasting Oregon Deaths During Record Heat

An extreme heat wave, estimated to be made 150 more times likely by climate change, affected much of Western North America from late June through mid-July 2021. In the United States, the heat wave affected Northern California, Idaho, Western Nevada, Oregon, and Washington. Often referenced informally as a heat dome, these record setting high temperatures were caused by a high-pressure system in which hot air was trapped over a single geographic area.

Oregon has made weekly deaths publicly available dating back to January 2020. This data includes three- and five-year averages going back to 2015. The scope of this project is to focus on Oregon death data to estimate the excess deaths caused by the heatwave. Given weekly averages for each multi-year timeframe, we can forecast expected deaths and compare the forecast to actual deaths. This will allow us to approximate the unexpected deaths related to unprecedented heat.

With the weekly deaths data provided by the Oregon Health Authority (OHA), in conjunction with daily temperature records, we can evaluate a time series of death trends. I explored the data to prepare for the forecast with consideration to an ARIMA model. I was prepared to use differencing to make the time series stationary, but this was not necessary after splitting the data into train and test. I proceeded to identify a model, estimate parameters, and check the model. The final output is a forecast used to compare to the actual deaths recorded by OHA. Evaluating the difference between forecast and actual resulted in my estimation of excess deaths during the period of record setting high temperatures.

### Problem Statement

Climate change is now impacting the planet Earth and its inhabitants more than ever since humans began keeping record of weather. From temperature extremes to droughts and floods, from forest fires to monstrous hurricanes, we are experiencing an unprecedented frequency and magnitude of deadly natural disasters. In a continued effort to educate and motivate people, governments, and businesses, we must understand the consequences of climate change and our dire need to act. 
