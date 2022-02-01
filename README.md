# World Weather Analysis
## Overview of the Analysis
World Weather Analysis project uses APIs to visualize weather data around the world. Also, we develop PlanMyTrip app to help planners to do vacation research, such as hotel, city, country, and weather information,ect. 
## Analysis Results
We create a customer travel destinations map, which depends on customer weather preferences. Those preferences can help them to identify potential travel destinations and hotels.The searching criteria as following:
  - City Name, Country code
  - Maximum Temperature
  - Current Description of weather
  - Latitude and Longitude of the City
  - Hotel Name

### Weather Maps Related
We use Google API to create Heatmaps, and perform weather data:
  - Latitude and Maximum Temperature
  - Latitude and Percent Humidity
  - Latitude and Percent Cloudiness
  - Latitude and Wind Speed
### Map Vacation Criteria
We use Google Maps Direction API to create vacation trip between four cities in Australia. The starting point is from city: Charters Towers to Ballian.

## Summary
World Weather Analysis project collect data by using Numpy module, OpenWeatherMap API to request weather from each unique city,Parse the JSON data from the API request. Through our exploratory analysis with visualization, we create heatmaps and pop-up markers to help users to plan their trips. Depending on customers' travel preferences, we could provide specific vacation information to planners.
