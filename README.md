# python-api-challenge
This is Python API Challenge by YK 
***"What is the weather like as we approach the equator?"

This activity is broken down into two deliverables, WeatherPy and VacationPy.

***Part 1: WeatherPy

In this deliverable, a Python script to visualize the weather of randomly selected 576 cities of varying distances from the equator was created. 

In this exercise citipy Python libraryLinks to an external site, the OpenWeatherMap API Links to an external site and a representative model of weather across cities was created.

The WeatherPy.ipynb Jupyter notebook was used. Python coding was used to develop a solution to address the required functionalities.

The code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination was provided.

Completed Requirement 1: Created Plots to Showcase the Relationship Between Weather Variables and Latitude

To fulfill the first requirement the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code was used. Also, a series of scatter plots to showcase the following relationships:

•	Latitude vs. Temperature
•	Latitude vs. Humidity
•	Latitude vs. Cloudiness
•	Latitude vs. Wind Speed

 was used and visuals can be found in Output folder in this GitHub repository.

Completed Requirement 2: A Linear Regression for Each Relationship was computed.

To fulfill the second requirement, the linear regression for each relationship was computed and plots were seperated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). A function in order to create the linear regression plots was written in code but later not used.

Next, a series of scatter plots was created. Linear regression line was added as well as the r-values.

Created following plots and after each pair of plots what the linear regression is modeling was explained and any relationship was described.

•	Northern Hemisphere: Temperature vs. Latitude
•	Southern Hemisphere: Temperature vs. Latitude
•	Northern Hemisphere: Humidity vs. Latitude
•	Southern Hemisphere: Humidity vs. Latitude
•	Northern Hemisphere: Cloudiness vs. Latitude
•	Southern Hemisphere: Cloudiness vs. Latitude
•	Northern Hemisphere: Wind Speed vs. Latitude
•	Southern Hemisphere: Wind Speed vs. Latitude

***Part 2: VacationPy

Weather data was used to plan future vacations using Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code imports the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1.

Main task was to use the Geoapify API and the geoViews Python library and employ Python skills to create map visualizations.

Following steps were completed:

1.	A map was created that displays a point for every city in the city_data_df DataFrame. The size of the point is Humidity of each city.
2.	By narrowing down the city_data_df DataFrame the ideal weather conditions were found for an ideal vacation with mild wind that has a speed in between 2 to 5 m/s, zero cloudiness and maximum temperatures between 20 to 35 Celsius.
3.	A new DataFrame called hotel_df twas created storing the city, country, coordinates, and humidity.
4.	For each city, the Geoapify API was used to find the first hotel located within 10,000 meters of your coordinates.
5.	The hotel names and countries were added as additional information in the hover message for each city on the map.


