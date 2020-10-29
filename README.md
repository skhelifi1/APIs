# APIs

## Weatherpy

* I randomly selected over 500 cities using latitudes and longitudes.
* I obtained the city names using citipy. 
* I then used open Weather API to obtain weather details such as humidity, temperature and wind speend...etc
* I created a Dataframe to store all that information.
* The Dataframe was then exported into a CSV file.
* Finally i used a series of scatter plots and linear regression to plot Temperature, Humidity %, Cloudiness% and Wind Speed Vs Latitudes.
* The scatter plots were also saved into a PNG image.
* I drew a few observations about the trends of the weather using the equator as a location reference.

## Vacationpy

* I created a heat map to display the humidity for every city from the weather data frame.
* I narrowed down the city list to a selection of cities based on the following criteria: Max Temperatue, Wind Speed and Cloudiness.
* Adatframe was created to store this new list of cities.
* Used Google Places API to locate the first hotel for each city in the list within 5000 meters of city coordinates.
* Finally, plotted the hotels on top of the heatmap.
