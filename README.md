# Python-API-Challenge
_____________________________________________________________________________________________________

# Table of Contents

  - General Info
  - Technologies
      
# General Info
_____________________________________________________________________________________________________

# What's the Weather Like?:

# WeatherPy
This script visualizes the weather of 500+ cities across the world of varying distance from the equator. The script utilizes a simple Python library and the OpenWeatherMap API to create a representative model of weather across world cities.
The first goal is to create a series of scatter plots to showcase the following relationships:

-Temperature (F) vs. Latitude
-Humidity (%) vs. Latitude
-Cloudiness (%) vs. Latitude
-Wind Speed (mph) vs. Latitude

The second goal is to run linear regression on each relationship. This time, the plots are separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

-Northern Hemisphere - Temperature (F) vs. Latitude
-Southern Hemisphere - Temperature (F) vs. Latitude
-Northern Hemisphere - Humidity (%) vs. Latitude
-Southern Hemisphere - Humidity (%) vs. Latitude
-Northern Hemisphere - Cloudiness (%) vs. Latitude
-Southern Hemisphere - Cloudiness (%) vs. Latitude
-Northern Hemisphere - Wind Speed (mph) vs. Latitude
-Southern Hemisphere - Wind Speed (mph) vs. Latitude

# VacationPy
This script uses jupyter-gmaps and the Google Places API to create a humidity heat map of the cities identified in WeatherPy, and then identifies the closest hotels for cities with ideal weather conditions.
-The heat map contains 3 layers: humidity heat map, hotel location pins, and information boxes containing the Hotel Name, City, and Country.

# Technologies 
_____________________________________________________________________________________________________

This challenge is completed with Python 3.8.5.
