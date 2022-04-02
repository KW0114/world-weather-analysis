# World Weather Analysis

## Overview and Purpose

This analysis was performed to get comfortable making API calls and creating customizable google maps created
from user specifications. In theory, this information could be used to create an app for customers to 
create a travel itinerary based on their preferred weather conditions. 

## Results

### Randomly Generated Geographic Coordinates

In Weather_Database, an original database was populated using the OpenWeatherMap API to retrieve data on each city.

[Weather_Database csv](https://github.com/KW0114/world-weather-analysis/blob/e5bc2f2ee09959e7f4437667697e809935e6a325/Weather_Database/WeatherPy_Database.csv)

### User Decides Weather Preferences

In Vacation_Search, the user can specify a maximum and minimum temperature preference for their trip. A google
maps figure is created with city markers detailing each city that fits their needs.

![screenshot](https://github.com/KW0114/world-weather-analysis/blob/e5bc2f2ee09959e7f4437667697e809935e6a325/Vacation_Search/WeatherPy_vacation_map.png)

### Travel Itinerary of Four Cities 

In Vacation_Itinerary, a google directions (driving) map is created for four cities chosen from a filtered 
database.

![screenshot](https://github.com/KW0114/world-weather-analysis/blob/e5bc2f2ee09959e7f4437667697e809935e6a325/Vacation_Itinerary/WeatherPy_travel_map.png)

![screenshot](https://github.com/KW0114/world-weather-analysis/blob/e5bc2f2ee09959e7f4437667697e809935e6a325/Vacation_Itinerary/WeatherPy_travel_map_markers.png)