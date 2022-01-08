# Python Weather Api:  What's the Weather Like?



![image](https://user-images.githubusercontent.com/86257908/148656638-43c5ed14-b90f-435f-a3a1-f3f2b0d1fde6.png)


## Task 

Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator, while utilizing a Python library, the
OpenWeatherMap API, and create a representative model of weather across worldcities.

Showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Run a linear regression on each relationship and separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere
(less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.

* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save a CSV of all retrieved data and a PNG image for each scatter plot.



