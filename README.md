# python-api_weather
Seeking to utilize Python requests, APIs, and JSON traversals to answer questions about how the weather might change as one approaches the equator.

**WeatherPy.ipynb:** Python script created to visualize the weather of 643 randomly selected cities across the world of varying distance from the equator; accomplished using data from the OpenWeatherMapAPI to create a representative model of weather across world cities.  Scatter plots of relationships, linear regression plots, and analysis in this notebook, and online here: 

https://stuhunter4.github.io/python-API_weather/WeatherPy/WeatherPy.html

- - -
![heatmap](WeatherPy/output_data/HeatMap_small.jpg)

**VacationPy.ipynb:** The second part of this challenge used a CSV file created in WeatherPy.ipynb, jupyter-gmaps and the Google Places API.  The final product of this is a heat map that displays humidity for each of the 643 cities.  API requests determined the first hotel within 5000 meters in cities that display ideal weather conditions, defined as having a max temperature lower than 80 degrees but higher than 70, wind speed less than 10 mph, and zero cloudiness.  The full-size heatmap can be found under: 

                WeatherPy/output_data/Humidity_HeatMap.png