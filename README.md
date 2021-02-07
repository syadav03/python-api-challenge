# python-api-challenge

Observations

1.  In the first graph in WeatherPy teh City Latitude Vs Temperature Graph shows that as the latitude increase the temperature decreases. This makes sense as the latitude increases means you are moving more north. It is currently winter season for the northern hemisphere. The graph shows this trend as well.

2. The Southern Hemisphere Max Temp Vs Latitude graph has a positive linear equation. This means that as latitude gets closer to the equator the max temperature increases. We know this to be true as the equator is one of the warmest parts of the earth.

3. The random cities that were filtered down from the csv in part by temperature wind and cloudiness were mostly cities in the southern hemisphere and near the equator.  This could be due to the fact that it is winter in the northern hemisphere and summe rin the southern hemisphere therefore meeting my vacation conditions.

Instructions 


In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.
The first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

After each plot, add a sentence or two explaining what the code is analyzing.
The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, take the time to explain what the linear regression is modeling. For example, describe any relationships you notice and any other analysis you may have.
Your final notebook must:

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.


Part II - VacationPy
Now let's use your skills in working with weather data to plan future vacations. Use jupyter-gmaps and the Google Places API for this part of the assignment.


Note: Remember that any API usage beyond the $200 credit will be charged to your personal account. You can set quotas and limits to your daily requests to be sure you can't be charged. Check out Google Maps Platform Billing and Manage your cost of use for more information.


Note: if you having trouble displaying the maps, try running jupyter nbextension enable --py gmaps in your environment and retry.


To complete this part of the assignment,you will need to do the following:


Create a heat map that displays the humidity for every city from Part I.

