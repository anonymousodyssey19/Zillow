# Zillow Project Overview:

I was brought onto this project to provide insights on where and how a Real Estate Investment Company should invest within the United States. Using Zillow's open source time-series data, I am able to analyze every zipcode in the country to find out the best strategy to pursue.

#### The definition of "best" is going to be zipcodes that have the highest projected increases in values over the next 3 years. 

# Project Results:

## The top 5 zip-codes are: 

94027 - $1,610,842.23 Projected Increase Home Values (24% ROI)

90210 - $1,485,517.35 Projected Increase Home Values (26% ROI)

94301 - $1,134,788.43 Projected Increase Home Values (25% ROI)

33480 - $1,107,069.31 Projected Increase Home Values (23% ROI)

94022 - $993,409.51 Projected Increase Home Values (24% ROI)

## Model Summary:

While I initially looked into creating my own SARIMA model with the data, I was not happy with the AIC and models ability to predict the home values in general. I looked into tuning the model until it became too computationally expensive and then opted to go with Facebooks Prophet Model to make the predictions shown above.
