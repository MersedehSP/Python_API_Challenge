## Python_API_Challenge
![Equator](Images/equatorsign.png)

## WeatherPy Code:

This code will create a set of random lat and lng combinations, puts them in a datframe. Then it Performs a weather check on each city using a series of successive API calls. you can see the city name printing as it's being processed.
It then will extract the information : City_ID, City_ame, Cloudiness, Country, Date,Humidity, Latitude and longitude, Maximim Temperature and Wind Speed and save them in lists. then it will make a final dataframe with those list and saves it as CSV.
Then it will plot the following graphs and saves a copy of graphs:

* Latitude vs. Temperature Plot
* Latitude vs. Humidity Plot
* Latitude vs. Cloudiness Plot
* Latitude vs. Wind Speed Plot

then there is a linear regression function that can be used for these type of analysis for the folllowing analysis: 

* Northern Hemisphere - Max Temp vs. Latitude Linear Regression
* Southern Hemisphere - Max Temp vs. Latitude Linear Regression
* Northern Hemisphere - Humidity (%) vs. Latitude Linear Regression
* Southern Hemisphere - Humidity (%) vs. Latitude Linear Regression
* Northern Hemisphere - Cloudiness (%) vs. Latitude Linear Regression
* Southern Hemisphere - Cloudiness (%) vs. Latitude Linear Regression
* Northern Hemisphere - Wind Speed (mph) vs. Latitude Linear Regression
* Southern Hemisphere - Wind Speed (mph) vs. Latitude Linear Regression


## VacationPy Code:

This code will take the CVS generated from WeatherPy and generates a heatmap.

Then it has the capability to narrow create a list of the cities based on specific criteria (in this code a new df created with cities with zero cloudiness, wind speed <10 and humidity<20).

Then it will serach for the closest Hotel to each of those citties, and adds the name of those cities to the dataframe. and fuinally, it will show the heatmap with the marker of each of those hotels. 
