# Vacation Itinerary Analysis
## Overview
In this project, we worked together with PlanMyTrip, a top travel technology company specialized in internet related services in the hotel and lodging industry.
This project will consisted in the following:
 1. Retrieve weather data including the weather description for over 500 cities across the world, given random longitudes and latitudes
 2. Give the customer a destination map
 3. Give the user a travel itinerary map.
## Resources
- <a href="https://openweathermap.org/current" target="_blank">Open Weather API</a>
- <a href="https://developers.google.com/maps/documentation/places/web-service/search" target="_blank">Google Maps and Places API</a>
- <a href="https://developers.google.com/maps/documentation/directions/overview" target="_blank">Google Directions API</a>
- Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Results
1. First, after creating random latitudes and longitudes we reitrieved city data going from latitude and longitude to a description of the current weather.
<img width="875" alt="Screen Shot 2022-01-31 at 8 55 18 PM" src="https://user-images.githubusercontent.com/95834653/151906608-73a0e993-1761-4863-b089-22b473b7fbf0.png">

2. With Jupyter's gmaps plugin, user's weather preference inputs and requests to the <a href="https://developers.google.com/maps/documentation/places/web-service/search" target="_blank">Google Maps and Places API</a>, the app generates a customer travel destinations map.
<img width="983" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/95834653/151906772-865ff094-9706-4bba-9740-077df17d31f6.png">

3. Using <a href="https://developers.google.com/maps/documentation/directions/overview" target="_blank">Google Directions API</a> the app generates a travel route between 4 cities selected by the user and default selected hotels.
<img width="895" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/95834653/151906852-2a747ebd-f8ae-477f-a616-134ebaa6c1e1.png">
<img width="833" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/95834653/151906920-b8c820b4-b9c9-4fef-821e-3855dfbd5d12.png">



