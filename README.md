# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Acquire POI rich data around bikeshare stations in a city and build a regression model to see if there is a pattern between the number of bikes in a location and the characteristics of the POIs in that location


## Process
* Load bike station data for city = ‘Abu Dhabi’ using bikeshare API
* Load venue/businesses data around bikeshare stations in city using foursquare and yelp APIs
* Join data from the two API’s and look for patterns in the  characteristics of the POIs near the bike stations
* Build a regression model to see if number of bikes in the station are affected by the characteristics of the POIs


## Results
Looking at the adj. R-squared value, we can see that the data does not fit a linear model at all. Additionally the p value for both the rating and popularity variables were both > 0.05 which tells us there is no statistical significant evidence to reject the null hypothesis that the coefficient for these variables were zero

## Challenges 
Could not find any data on the bikeshare locations using the Yelp API, which impacted my results quite a bit because I wouldnt find any additional charecteristics to my POIs such as # of reviews.

## Future Goals
If i had more time I would try and parse for more various POIs near the stations and also for greater detailed characteristics for these POIs
