# World_Weather_Analysis

## Purpose 

The purpose of this project was to generate an app where users may enter their weather preferences, generate a list of cities and nearby hotels that fit their searches, and create an itinerary to travel between hotels and cities nearby. There were three main parts to the project:
	1. Generate a weather database. In this code, 2000 random pairs of latitudes and longitudes were generated and then their nearest cities were found using citipy. The weather details of those cities were then retrieved using OpenWeatherMap's API. 
	2. Next, a script was written to pull user information on their weather preferences for vacation spots and generate a map with city markers that fit their search parameters. Hotel information near those city preferences were generated on a map using Google's Nearby Search API. 
	3. Finally, a script was written to develop an itinerary map between nearby cities using Google's Directions API. 