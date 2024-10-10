# WeatherApp

A Python-based weather application that displays the current weather for any given city. The application allows the user to enter a city name, fetches real-time weather data using the OpenWeatherMap API, displays the temperature, a brief weather description, and an emoji to visually reprensent the weather.

## Features:
• City Input: Enter the name of the city of which you want to check the weather
• Weather Display: Shows the current temperature in Celsius
• Weather Description: Provides a brief description of the weather
• Weather Emoji: Displays an emoji to represent the weather (e.g. ☀️ for sunny)
• Error Handling: Provides error messages for various errors, e.g. network issues

## Technologies:
• Python - Main programming language
• PyQt5 - GUI
• Requests - Handles HTTP requests to fetch weather data from API
• OpenWeatherAPI - Provides real time weather data

### Future Improvements:
• Allow user to choose from celsius or fahrenheit
• Include more detailed weather information such as humidity, wind speed etc
• Allow user to enter country in case of duplicate city names (e.g. Birmingham UK & Birmingham Alabama USA, and Sydney, Australia & Sydney, Nova Scotia, Canada)
