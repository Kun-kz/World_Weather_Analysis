# World Weather Analysis
## Overview
### Original Project Overview
In this project, we generated random latitude and longitude of world cities, collected weather data across cities by performing an API call with the OpenWeatherMap, created plots, determined weather data correlations, and used a Google API to create heatmaps.
### Challenge Overview
The challenge consisted of three technical analyses. It provided real-time hotel suggestions and weather description for clients by using two APIs.
-	Retrieve Weather Data
-	Create a Customer Travel Destinations Map
-	Create a Travel Itinerary Map

## Resources
-	Data Source: WeatherPy_Database.csv ( in the Weather_Database folder)
-	Software: Python 3.7.6

## Summary
A set of 2,000 random latitudes and longitudes was generated, the nearest cities were retrieved, current weather data was collected and saved in WeatherPy_Database.csv.

The hotel suggestions were provided when clients entered their minimum and maximum temperature criteria for their vacations. A marker layer map that would have pop-up markers for each hotel in each city on the map was created and the sample was saved in Vocation_Search folder.

A travel itinerary that showed the route between four cities chosen from the customer’s possible travel destinations was created by using the Google Directions API. We also made the marker layer map with a pop-up marker for each city.
