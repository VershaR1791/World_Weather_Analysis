# World_Weather_Analysis
Google Maps API an Open Weather Maps API was used to create a PlanMyTrip App for customers
## Deliverable 1
Retrieving Weather Data from Open Weather Maps API:
 - First step was to generate 2000 random latitude and longitude combinations
 - Using citipy a list to hold over 500 cities df was created
 - Open Weather Maps API and base url was used to create a city_data df which stores all weather related information for each city
 - This was saved into an excel format
## Deliverable 2
Creating a Customer Travle Destinations Map:
 - Weather database was imported into a new df
 - User inputs were requested for temperature (min and max) and cities within that temp range was added into another df
 - Google Nearby Search API url and API was used to find hotels within 5000 meters of each city and stored in df and converted to excel csv.
 - Markers were added to map layer to give information related to city, temperature, weather conditions and hotel
![WeatherPy_Vacation_Map](https://user-images.githubusercontent.com/84694664/128639580-7b13c591-1ee2-4e8f-a8cf-43ecef07497d.PNG)

## Delivarable 3
Creating a Travel Itnerary Map
 - Vacation list csv was imported in a new df and 4 nearby cities were selected for travel
 - The same city name was passed to start and end cities. The other 3 cities were added as stops
 - The latitude and longitude was passed as tuples
 - Gmaps direction layer was added to get the driving routes
 - Itinerary df was created for the four cities and the hotel information was passed to it.
![WeatherPy_travel_map](https://user-images.githubusercontent.com/84694664/128639682-5fbd30a2-cbd9-4f49-9f2c-07902e517c62.PNG)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/84694664/128639684-a12abb56-7695-4953-ab2d-b16dbddb3906.PNG)
