# World_Weather_Analysis
## Overview
Beta testers recommended a few changes to take the PlanMyTrip app to the next level to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.


## Resources
- **Data Source(APIs)**: citipy, jupyter-gmaps, OpenWeatherMap API, Google Maps and Places API, Google Maps Directions API
- **Software:** Python 3.7, Anaconda Navigator, Jupyter Notebook 

## Results
### Weather Database

The weather data is retrieved for all identified cities through a user request to the OpenWeatherMap API.


<img width="919" alt="Screen Shot 2021-11-30 at 5 41 08 PM" src="https://user-images.githubusercontent.com/92277581/144145681-f29d8f31-04f0-4fe9-b967-646b45795897.png">


### Vacation Search

PlanMyTrip app generates a customer travel destinations map as per user's weather preference inputs, using Jupyter's gmaps plugin and the Google Maps and Places API.


<img width="1072" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/92277581/144145566-0a62ab92-a914-4f84-b57d-fe0d3c8844a8.png">

### Vacation Itinerary

Using Google Maps Directions API, the app generates a travel route between 4 cities selected by the user.

<img width="976" alt="Screen Shot 2021-11-29 at 8 51 48 PM" src="https://user-images.githubusercontent.com/92277581/144145607-2137791a-4cbf-4528-a86b-0c2722867e89.png">

