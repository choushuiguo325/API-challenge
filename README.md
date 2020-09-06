# Python API Homework - What's the Weather Like?


## Part I - WeatherPy

A Python script "WeatherPy.ipynb" inside the WeatherPy folder is created to visualize the weather of 500+ cities across the world of varying distance from the equator, which utilizes a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

1. A series of scatter plots are created to showcase the following relationships and sentences or two explaining what the code is and analyzing are added after each plot :

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude


2. Linear regressions get running on each relationship, which ares eparated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, explainations about what the linear regression is modeling such as any noticed relationships and any other analysis are shown.


All the scatter plots are exported into output_data folders as png figures.

### Part II - VacationPy

1. A Python script "VacationPy.ipynb" inside the VacationPy folder is created to decide future vacation plan.
2. A heat map that displays the humidity for every city from the part I is created.
3. The dataframe is narrowed down depending on the following rules to find ideal weather condition

  * A max temperature lower than 80 degrees but higher than 70.
  * Wind speed less than 10 mph.
  * Zero cloudiness.
  * Drop any rows that don't contain all three conditions.
  
4. The first hotel for each city located within 5000 meters of the coordinates is found using Google Places API.
5. The hotels are plotted on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.




