# Python_APIs
## Background
Creating a `Python script` to visualize the weather of 500+ cities across the world of varying distance from the equator using [CityPy](https://pypi.org/project/citipy/), a simple Python library, and the [OpenWeatherMap API](https://openweathermap.org/api).
## Objectives
Building a series of scatter plots to showcase the following relationships:
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

The script accomplishes the following:
- Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.
- Performs a weather check on each of the cities using a series of successive `API calls`.
- Includes a print log of each city as it's being processed with the city number and city name.
- Saves both a CSV of all data retrieved and png images for each scatter plot.
## Observable Trends
- Not surprisingly, temperature increases as we approach the equator. However, temperature peaks at around 20 degrees latitude, not exactly at the equatorial line. This may be due to the Earth's tilt in the axis known as obliquity.
- Cloudiness and humidity do not show a strong correlation to latitude. The visualizations below show a great variety of values at similar latitudes.
- Wind speed appears to slightly increase as we move away from the equator. We would need to go beyond the ranged examined to make a definitive conclusion.

![Image](

