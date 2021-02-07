# World_Weather_Analysis

## Overview
In this project, I created a program to recommend hotels and travel destinations to users based on their weather preferences (specifically temperature). 
I collected data using APIs from "Open Weather Data" as well as "Google Map Platform".

## Weather Data 
 1. First, I randomly generated latitude and longitude combinations. I generated enough so that when I applied the nearest city function using the citipy module, the cities generated were a good representation of the habitable land mass of the planet.
 
 2. I generated a dataset of cities that was well distributed around the world. 
 
 3. I pulled the weather data for all the cities and gathered the data in a Pandas dataframe.
 
## Vacation Search
 1. I added user inputs to see what the user's minimum and maximum temperature preferences were.
 
 2. I used these preferences to filter the cities in the weather data dataframe.
 
 3. Next, I found hotels within 5000m of these cities using the google directions API.
 
 3. Lastly, I used the API to map all the hotels on a map using markers.
 
 <img src = "https://github.com/Kee2u/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png?raw=true">
 
 ## Vacation Search
  1. Finally, I created a travel itinerary using 4 cities that were close to each other.
  
  2. I used the google directions API to display this on a map as well.
  
   <img src = "https://github.com/Kee2u/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG?raw=true">
  
  
