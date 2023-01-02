# World_Weather_Analysis
## Overview of the analysis
A hypothetical travel company, PlanMyTrip, needs an app that will provide customers with real-time suggestions for their ideal hotels. I will create a custom itinerary based on weather preferences and hotel data for global cities. A unique feature of this app is the customized driving itinerary mapped out between 4 cities. 

I will use Python libraries and modules, and will retrieve and use data from an API "get" request for weather and mapping. 

Additional coding is included to create scatter plots and perform linear regression. For the final deliverable, a map was created using GeoViews and the GeoApify API, showing four cities plotted in Mexico, with a driving route laid out between them. 

## Resources
- Data sources: WeatherPy_Database.csv, WeatherPy_vacation.csv
- Software: Python 3.9, Jupyter Notebook v6
- Python libraries: pandas, numpy, citipy, geoviews, hvplot.pandas, requests

## Challenge Solution
[Challenge Deliverable 1 Solution](https://github.com/EBolinVA/World_Weather_Analysis/tree/main/Weather_Database): The solution files for the module challenge's first deliverable are located in this folder.

[Challenge Deliverable 2 Solution](https://github.com/EBolinVA/World_Weather_Analysis/tree/main/Vacation_Search): The solution files for the module challenge's second deliverable are located in this folder.

[Challenge Deliverable 3 Solution](https://github.com/EBolinVA/World_Weather_Analysis/tree/main/Vacation_Itinerary): The solution files for the module challenge's third deliverable are located in this folder.

## Results

To help PlanMyTrip recommend ideal hotels based on clients' weather preferences, I must first collect and analyze worldwide weather data in different cities.

I created a Pandas DataFrame with >500 unique cities around the world and their weather data in real time, using NumPy, citipy, and the OpenWeatherMap API. Then I created the custom map with Geoapify and GeoViews, which allowed me to get the nearest hotels to the given locations. Hotels were found within a specific radius of the city coordinates where customers travel. 

![Image of map with cities plotted](https://github.com/EBolinVA/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

Four cities in Mexico were chosen for the final output, a travel itinerary map showing the route beginning at a starting point, stopping at three other cities, and then returning to the original city. 

![Image of Itinerary map with 4 Mexican cities](https://github.com/EBolinVA/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

## Recommendations

This project has the potential for a variety of applications for the travel customers of PlanMyTrip. The GeoApify location platform has multiple APIs which return a plethora of information. The Routing API used in this code to find a driving route between cities, can also be optimized to search heavy truck routes (deliveries), public transportation routes, mountain bike routes, and even hikes. One can also specify avoiding toll roads and highways. 


