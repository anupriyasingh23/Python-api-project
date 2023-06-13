# Python-api-project

This repository contains the code and files for the Python API Challenge assignment. The assignment is divided into two parts: WeatherPy and VacationPy.

WeatherPy
In the WeatherPy part, a Python script is created to visualize the weather of over 500 cities of varying distances from the equator. The citipy Python library and the OpenWeatherMap API are used to generate random geographic coordinates and retrieve weather data for each city.

Files
api_keys.py: This file contains the API key required to access the OpenWeatherMap API. Please note that this file is included in the .gitignore file to prevent it from being shared publicly.
WeatherPy.ipynb: This Jupyter notebook contains the code and instructions to perform the weather analysis. It guides you through the process of using Python coding skills to develop a solution and visualize the relationships between weather variables and latitude.
Requirements
The requirements for the WeatherPy part include:

Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code.
Create scatter plots to showcase the relationship between latitude and the following weather variables:
Temperature
Humidity
Cloudiness
Wind Speed
Compute linear regression for each relationship and create scatter plots with linear regression lines for both the Northern Hemisphere and the Southern Hemisphere.
VacationPy
In the VacationPy part, the weather data skills are used to plan future vacations. The geoViews Python library and the Geoapify API are utilized to create map visualizations.

Files
VacationPy.ipynb: This Jupyter notebook contains the code and instructions to plan future vacations based on weather conditions. It includes the creation of maps displaying cities, filtering cities based on weather conditions, and finding hotels near selected cities.
Requirements
The requirements for the VacationPy part include:

Create a map that displays a point for every city in the city_data_df DataFrame.
Narrow down the city_data_df DataFrame to find cities with ideal weather conditions.
Use the Geoapify API to find the first hotel located within 10,000 meters of the coordinates for each city.
Add the hotel name and country as additional information in the hover message for each city on the map.
Instructions
To complete this assignment, follow the steps below:

Create a new repository for this project called python-api-challenge. Do not add this homework to an existing repository.
Clone the new repository to your computer.
Inside your local Git repository, create a directory for this assignment with a folder name that corresponds to the challenges, such as WeatherPy.
Inside the folder you just created, add the files called api_keys.py, WeatherPy.ipynb, and VacationPy.ipynb from the provided starter code.
Before pushing your changes to GitHub, add a .gitignore file to prevent the api_keys.py file from being shared publicly. Open the .gitignore file and add the following line: api_keys.py.
Commit your changes and push them to GitHub.
Follow the instructions provided in the WeatherPy.ipynb and VacationPy.ipynb notebooks to complete the required tasks for each part of the assignment.
Note: Make sure to replace YOUR_API_KEY in the api_keys.py file with your actual API key for the OpenWeatherMap API.
