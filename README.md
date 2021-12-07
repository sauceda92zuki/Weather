# Weather-Dashboard




# Project Description



In this app, the user enters the name of a city (either just the city name, or "city, state") in the search field, then clicks the search button.  The app will display the current weather conditions in that city, including temperature, humidity, UV index, and a picture representing whether it is clear, cloudy, raining, etc.  Additionally, a 5-day forecast for that city is displayed below the current conditions showing similar information (predicted at 12:00 PM on each day).

# Challenges, Opportunities for Improvement

This app was created using the Open Weather Map data API.  In order to get all the information needed, a good deal of manipulation of the response from the get request was needed, including taking information from one response to generate a new request.  For example, the initial search based on city name returns latitude and longitude coordinates, and these coordinates are used in the UV Index get request.

