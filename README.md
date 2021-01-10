# Python-API-Challenge
-------------------------
# Part I - WeatherPy 

I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities. 

I created a series of scatter plots to showcase the following relationships:
- Temperature (F) vs. Latitude 
- Humidity (%) vs. Latitude 
- Cloudiness (%) vs. Latitude 
- Wind Speed (mph) vs. Latitude 

I also ran a linear regression on each relationship. The plots are separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
- Northern Hemisphere - Temperature (F) vs. Latitude 
- Southern Hemisphere - Temperature (F) vs. Latitude 
- Northern Hemisphere - Humidity (%) vs. Latitude 
- Southern Hemisphere - Humidity (%) vs. Latitude 
- Northern Hemisphere - Cloudiness (%) vs. Latitude 
- Southern Hemisphere - Cloudiness (%) vs. Latitude 
- Northern Hemisphere - Wind Speed (mph) vs. Latitude 
- Southern Hemisphere - Wind Speed (mph) vs. Latitude
 

The final notebook includes:
500 randomly selected unique (non-repeat) cities based on latitude and longitude. A weather check on each of the cities using a series of successive API calls. Includes a print log of each city as it's being processed with the city number and city name. A saved CSV of all retrieved data and a PNG image for each scatter plot.

--------------------------------------
# Part II - VacationPy 

For this part of my project, I completed the following:

- Created a heat map that displays the humidity for every city from Part I.
-Narrowed down the DataFrame to find my ideal weather condition. 
-- A max temperature lower than 80 degrees but higher than 68.
-- Wind speed less than 10 mph.
-- Almost Zero cloudiness.
- Used Google Places API to find the first hotel for each city located within 5000 meters of the coordinates of my ideal location based on weather.
- Plotted the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
