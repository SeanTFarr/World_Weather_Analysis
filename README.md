# World_Weather_Analysis
## Overview
After the initial launch of the PlanMyTrip app, Jack, the head of analysis for the user interface team, recommended a few changes to take the app to the next level. Those changes involved adding a weather description to the weather data that we have already retrieved, utilize input statements to filter the data for the clients weather preferences, which will be used to identify possible travel destinations. Once we have that list, we will choose 4 cities to create a travel itinerary that will include a travel route as well as a marker layer map with details that include the current weather description.


## Results

Using the temperature requests from the client, we narrowed down potential travel destinations:
<img src=Vacation_Search\WeatherPy_vacation_map.png >
Going through the potential travel destinations, we found four cities that were within the same region that we could give as a possible destination.
Using Google Maps DIrections API, we created a travel route between those four cities.


<img src=Vacation_Itinerary\WeatherPy_travel_map.png>

Also utilizing Google Maps API, we generated map markers giving the recommended hotl name, they  city, the country, the current weather description and the maximum temperature.

<img src=Vacation_Itinerary\WeatherPy_travel_map_markers.png>

## Summary
The end result was a possible dream vacation for our client, including trip destination itinerary, that was based on their preferred temperature range.