# Bike Sharing Demand Prediction

Bike sharing has become very popular in major cities as an alternative transportation mode. Bike rental and return is administered through automated kiosk locations all aroud the city.

## Goal of the Project

The goal of the project is to predict the demand of the bikes in a given day and hour. Root mean square logarithmic error (RMSLE) will be utilized for evaluation. RMSLE logs each RMSE and penalizes underestimated error more than overestimated errors.

## Data 

Following are the features and their descriptions:

- datetime
- season. 1 = spring, 2 = summer, 3 = fall, 4 = winter
holiday. whether the day is a holiday or not
- workingday. whether the day is neither a weekend nor holiday
weather.
- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp - temperature in Celsius
- atemp - "feels like" temperature in Celsius
- humidity - relative humidity
- windspeed - wind speed
- casual - number of non-registered user rentals initiated
- registered - number of registered user rentals initiated
- count - number of total rentals (Dependent Variable)

Data can be downloaded from: https://www.kaggle.com/c/bike-sharing-demand/data
