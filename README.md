# PORTFOLIO-API-INTEGRATION-AND-DATA-VISUALIZATION

**Name**: ADIL SHAIKH

**Company**: CODETECH IT SOLUTIONS

**ID**: CT08DJS

**Domain**: Python Programming

**Duration**: 12th December to 12th January

**Mentor**: Neela Santhosh Kumar

# OUTPUT OF THE TASK

![OUTPUT](https://github.com/user-attachments/assets/096e252c-01c3-4e73-870e-b714b0bf87c2)


# Project Overview: Weather Data Visualization
This project is designed to fetch, parse, and visualize weather data for a specified city using the OpenWeatherMap API. 
The primary goal is to provide a clear graphical representation of temperature trends over time, allowing users to easily understand how temperatures fluctuate.

# Key Components:

# Data Fetching:

The project utilizes the OpenWeatherMap API to retrieve weather forecast data for a specified city.
The fetch_weather_data function constructs the API request URL, sends the request, and handles the response.
If the request is successful (HTTP status code 200), it returns the JSON data; otherwise, it prints an error message.

# Data Parsing:

The parse_weather_data function processes the JSON data returned from the API.
It extracts timestamps and corresponding temperature values, organizing them into a Pandas DataFrame for easier manipulation and analysis.

# Data Visualization:

The plot_weather_data function creates a line plot using Seaborn and Matplotlib to visualize the temperature trends over time.
The plot includes labeled axes, a title, and formatted timestamps for better readability.

# Main Script Execution:

The script is designed to be run as a standalone program.
It defines the API key and the city for which the weather data will be fetched.
It orchestrates the fetching, parsing, and plotting of the weather data by calling the respective functions in sequence.

# Usage Instructions:

To use this project, you need to replace the placeholder API key with a valid OpenWeatherMap API key.
You can change the CITY variable to fetch weather data for a different location.
Running the script will display a line plot of the temperature trend for the specified city.

# Dependencies:

The project requires the following Python libraries:

requests: For making HTTP requests to the OpenWeatherMap API.
matplotlib: For creating static, animated, and interactive visualizations in Python.
seaborn: For making statistical graphics in Python, built on top of Matplotlib.
pandas: For data manipulation and analysis, particularly for handling the DataFrame.

# Potential Enhancements:

Implement error handling for cases where the city is not found or the API key is invalid.
Allow users to input the city name and API key via command line arguments or a user interface.
Extend the functionality to include additional weather parameters (e.g., humidity, wind speed) in the visualization.
Add options for different types of visualizations (e.g., bar charts, scatter plots) or time intervals (e.g., daily, weekly).

This project serves as a practical example of how to integrate API data into a Python application and visualize it effectively, making it a useful tool for anyone interested in weather trends.




