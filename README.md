# World_Weather_Analysis
## Project Overview

The following repository includes deliverables related to the collection and analysis of real-time weather data for the purpose of making hotel recommendations for PlanMyTrip.

PlanMyTrip uses the data to recommend ideal hotels based on clients’ weather preferences.

The deliverables for this project include:
* Scatter plots of the weather data to determine corrrelations for the following comparisons:
    * Latitude versus temperature
    * Latitude versus humidity
    * Latitude versus cloudiness
    * Latitude versus wind speed
* Heatmaps using the Google Maps and Places API that showcases the following:
    * Latitude and temperature
    * Latitude and humidity
    * Latitude and cloudiness
    * Latitude and wind speed
* Heatmaps with pop-up markers that can display information on specific cities based on a customer’s travel preferences

### Challenge
To further enhance the above deliverables, the following ehnancments were made to the app:
* Pop-up markers were enhanced to include a current weather description so customers can know the weather as they are traveling
* The ability for customers who are making travel decisions in real-time to indicate rain and snow preference as part of the search criteria to indicate if it is raining or snowing
* The app includes a map that shows the directions for customers’ travel itinerary


## Resources
Data Source (APIs): OpenWeatherMap, Google Maps, Google Places, Google Directions
Software: Python 3.7.6, Jupyter Lab 1.2.6
Libraries: CitiPy, Datetime, Gmaps, NumPy, Matplotlib, Pandas, Requests,  SciPy, Time


## Summary
The following is a list of Jupyter notebooks which include all the code for the PlanMyTrip application:
* WeatherPy.ipynb
* Weather_Database.ipynb (challenge)
* VacationPy.ipynb
* Vacation_Search.ipynb (challenge)
* Vacation_Itinerary.ipynb (challenge)

Below is a sample of maps generated on 2020-04-03 when the search criteria included the following prameters related to the current weather conditions:
* Minimum temperature = 70°F
* Maximum temperature = 90°F
* Rain preference = no
* Snow preference = no

This is the full map of cities which met the weather criteria:
![](https://github.com/karenbennis/World_Weather_Analysis/blob/master/images/WeatherPy_travel_map.png)

Five cities (Porto Velho, Camana, Alta Floresta, Pisco, and Tarata) were selected as the travel destinations to be included on the itinerary, as shown in the map below:
![](https://github.com/karenbennis/World_Weather_Analysis/blob/master/images/WeatherPy_vacation_map.png)

The following map shows the directions for the driving trip Pisco to Tarata via Camana, Porto Velho, and Alta Floresta.
![](https://github.com/karenbennis/World_Weather_Analysis/blob/master/images/WeatherPy_vacation_map_markers.png)