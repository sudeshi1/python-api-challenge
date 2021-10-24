# Python API - What's the Weather like?

## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's answer a fundamental question: "What's the weather like as we approach the equator?"
Now, we know, "Duh. It gets hotter..." But, if pressed, how would you prove it?

![Weather](/Images/weather.gif)

## Accomplishments

### Part 1: WeatherPy

In the first part, a Python script was created to visualize the weather of 500+ cities across the world of varying distance from the equator. 

#### Requirements

1. A simple Python Library: *citipy*

2. *OpenWeatherMap API*

#### Tasks

- Create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude

![Temperature (F) vs. Latitude](/Images/lat_temp)

* Humidity (%) vs. Latitude

![Humidity (%) vs. Latitude](/Images/lat_humid)

* Cloudiness (%) vs. Latitude

![Cloudiness (%) vs. Latitude](/Images/lat_cloud)

* Wind Speed (mph) vs. Latitude

![Wind Speed (mph) vs. Latitude](/Images/lat_speed)

- Run linear regression on each relationship by separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude)

* Northern Hemisphere - Temperature (F) vs. Latitude

![Northern Hemisphere - Temperature (F) vs. Latitude](/Images/north_lat)

* Southern Hemisphere - Temperature (F) vs. Latitude

![Southern Hemisphere - Temperature (F) vs. Latitude](/Images/south_lat)

* Northern Hemisphere - Humidity (%) vs. Latitude

![Northern Hemisphere - Humidity (%) vs. Latitude](/Images/north_humid)

* Southern Hemisphere - Humidity (%) vs. Latitude

![Southern Hemisphere - Humidity (%) vs. Latitude](/Images/south_humid)

* Northern Hemisphere - Cloudiness (%) vs. Latitude

![Northern Hemisphere - Cloudiness (%) vs. Latitude](/Images/north_clouds)

* Southern Hemisphere - Cloudiness (%) vs. Latitude

![Southern Hemisphere - Cloudiness (%) vs. Latitude](/Images/south_clouds)

* Northern Hemisphere - Wind Speed (mph) vs. Latitude

![Northern Hemisphere - Wind Speed (mph) vs. Latitude](/Images/north_wind)

* Southern Hemisphere - Wind Speed (mph) vs. Latitude

![Southern Hemisphere - Wind Speed (mph) vs. Latitude](/Images/south_wind)

### Part 2: VacationPy

#### Requirements
1. *jupyter-gmaps*

2. *Google Places API*, *Maps JavaScript API*

#### Tasks

- Create a heat map that displays the humidity for every city from Part I

![Heat Map](!/Images/map1.png)

- Narrow down the DataFrame to find your ideal weather condition. For example:
1. A max temperature lower than **80 degrees but higher than 70**
2. Wind speed less than **10 mph**
3. Zero cloudiness

- Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country

![Heat Map - Hotel](!/Images/map2.png)

## Observations

1. Climates in the Southern Hemisphere are milder than those in the Northern Hemisphere at equivalent latitudes. This is due to the fact that the Southern Hemisphere has far more ocean and far less land, because water heats and cools far more slowly than land.

2. The highest temperature is found at 0 latitude, and temperature lowers as latitude climbs or decreases. This occurs because the equatorial region receives sunlight straight, with little or no angle, due to the earth's curvature shape.

3. Wind speed is not strongly influenced by latitude. The strength of the air pressure gradient determines the wind speed; the greater the pressure gradient, the faster the wind.

[WeatherPy](/WeatherPy/WeatherPy.ipynb)

[VacationPy](/VacationPy/VacationPy.ipynb)

[Output CSV File](/WeatherPy/output.csv)

