# "What's the weather like as we approach the equator?"



## WeatherPy

 A Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, [simple Python library](https://pypi.python.org/pypi/citipy),  and the [OpenWeatherMap API](https://openweathermap.org/api) have been used.

### Objectives
To build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

This project:

* Randomly selects **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Performs a weather check on each of the cities using a series of successive API calls.
* Includes a print log of each city as it's being processed with the city number and city name.
* Saves both a CSV of all data retrieved and png images for each scatter plot.
* Includes a written description of three observable trends based on the data.



