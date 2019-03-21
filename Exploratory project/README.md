# Exploratory project

## Questions to be investigated
- predict Beijing air quality level of year 2015 based on the model trained on our current 
dataset. 

## Dataset information
Description of the data set (source, variables, the number of variables and observations intended to use in the analysis):
- Source: https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data#
- Number of observations: 43824
- Number of variables: one predictor and seven variables
- response: pm2.5: PM2.5 concentration (ug/m^3) 
- variables: (We choose 2012 and 2013 year data)
  - DEWP: Dew Point (â„ƒ)
  - TEMP: Temperature (â„ƒ)
  - PRES: Pressure (hPa)
  - cbwd: Combined wind direction
  - Iws: Cumulated wind speed (m/s)
  - Is: Cumulated hours of snow
  - Ir: Cumulated hours of rain

## Statistical learning tools to use
- linear regression
- LDA/QDA/KNN/Logisti
- Support Vector Machine/PCR/PLS/Ridge/lasso
- Selection methods including forward/backward/AIC/BIC
