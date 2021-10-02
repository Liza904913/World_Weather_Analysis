# World_Weather_Analysis

## Project Overview

In this analysis we need: 
- Retrieve Weather Data
- Create a Customer Travel Destinations Map
-  Create a Travel Itinerary Map

## Summary

We enerate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data, using API, we got he current weather description for each city. 

By using input statements we retrieved customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

By using the Google Directions API we created a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, we create a marker layer map with a pop-up marker for each city on the itinerary.

![Hotel_info.png](weather_data/Hotel_info.png)

![Locations.png](weather_data/Locations.png)
