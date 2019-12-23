# Python_APIs
## Background
Creating a `Python script` to visualize the weather of 500+ cities across the world of varying distance from the equator using [CityPy](https://pypi.org/project/citipy/), a simple Python library, and the [OpenWeatherMap API](https://openweathermap.org/api).
## Objectives
Building a series of scatter plots to showcase the following relationships:
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude 
- Wind Speed (mph) vs. Latitude
 
A Python script accomplishes the following:
- Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude. 
- Performs a weather check on each of the cities using a series of successive `API calls`.
- Includes a print log of each city as it's being processed with the city number and city name.
- Saves both a CSV of all data retrieved and png images for each scatter plot.
## Observable Trends
- Not surprisingly, temperature increases as we approach the equator. However, temperature peaks at around 20 degrees latitude, not exactly at the equatorial line. This may be due to the Earth's tilt in the axis known as obliquity.
- Cloudiness and humidity do not show a strong correlation to latitude. The visualizations below show a great variety of values at similar latitudes.
- Wind speed appears to slightly increase as we move away from the equator. We would need to go beyond the ranged examined to make a definitive conclusion.

![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture1.PNG)
### Generating Cities List

![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture2.PNG)
### Performing API Calls
- Performing a weather check on each city using a series of successive API calls
- Including a print log of each city as it's being processed (with the city number and city name)

![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture3.PNG)
### Converting Raw Data to DataFrame
- Exporting the city data into a [weather_data.csv](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Output_csv/weather_data.csv)
- Displaying the DataFrame

![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture4.PNG)
![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture5.PNG)
![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture6.PNG)
![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture7.PNG)
### Plotting the Data
- Using a proper labeling of the plots using plot titles (including date of analysis) and axes labels
- Save the plotted figures as pngs
#### Latitude vs. Temperature Plot 

![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture8.PNG)
#### Latitude vs. Humidity Plot

![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture9.PNG)
#### Latitude vs. Cloudiness Plot

![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture10.PNG)
#### Latitude vs. Wind Speed Plot

![Image](https://github.com/mserobabina/Python_APIs/blob/master/WeatherPy/Capture11.PNG)
