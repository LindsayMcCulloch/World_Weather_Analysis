# python-api-challenge
This is the repository for Monash University Data Analytics Bootcamp Module 6 Challenge

# How to use
The main file/s are the Jupyter Notebooks: WeatherPy.ipynb and VacationPy.ipynb

Running these files will produce all of the used DataFrames and created graphs  

Analysis of graphs and visual report can be found in - Module 6 challenge.docx  

Background:
--------------------------------------------------------------------------------------------------------------------------------
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

Part 1: WeatherPy
--------------------------------------------------------------------------------------------------------------------------------
In this deliverable, you'll create a Python script to visualise the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

# Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

# Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values to create the following plots:

Northern Hemisphere: Temperature (C) vs. Latitude

Southern Hemisphere: Temperature (C) vs. Latitude

Northern Hemisphere: Humidity (%) vs. Latitude

Southern Hemisphere: Humidity (%) vs. Latitude

Northern Hemisphere: Cloudiness (%) vs. Latitude

Southern Hemisphere: Cloudiness (%) vs. Latitude

Northern Hemisphere: Wind Speed (m/s) vs. Latitude

Southern Hemisphere: Wind Speed (m/s) vs. Latitude

After each pair of plots, explain what the linear regression is modelling. Describe any relationships that you notice and any other findings you may uncover.

Part 2: VacationPy
--------------------------------------------------------------------------------------------------------------------------------

In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualisations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

# Requirements

1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

2. Narrow down the city_data_df DataFrame to find your ideal weather condition.

3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

4. For each city, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.
   
5. Add the hotel name and the country as additional information in the hover message for each city in the map

Resources used:
--------------------------------------------------------------------------------------------------------------------------------
BCS Xpert Learning assistant 
Office Hours
https://stackoverflow.com/questions/10336614/scatter-plot-in-matplotlib
https://www.geoapify.com/maps-api
https://stackoverflow.com/questions/52542451/control-what-text-is-shown-on-hover
https://stackoverflow.com/questions/59829077/how-to-display-r-squared-value-on-my-graph-in-python



