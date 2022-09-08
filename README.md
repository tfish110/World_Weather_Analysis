# World_Weather_Analysis
## Summary

For this project, we used data drawn from OpenWeatherMap and Google Maps through their APIs to create our own custom vacation itinerary. We used random number functions to generate a list of latitude and longitude pairs, and then used the data from OpenWeatherMap's API to generate a map of weather around the world based on those latitude and longitude pairs by way of the Google Maps API.

Next, we wrote code in Python to prompt a desiered temperature range for vacation destinations. Using the entry from that prompt, we then narrowed the map of locations to those whose temperature date fell in the desired range. We then added info boxes to the markers for each remaining location.

From there, we used the Google Maps API to search for the nearest hotel to each location on the map, and added that information to the info boxes for the map markers.

After selecting a cluster four of locations that could be traversed by car, we used the option to add a directions layer to a map with only those four cities' markers remaining. We then added back the marker info boxes for a version of the map with only those four cities of interest.

## Resources
- Software: Python 3.7.13, Anaconda command line client 1.9.0, Conda 4.13.0, Jupyter Notebook 6.4.8, Pandas 1.3.5, NumPy 1.21.5, Requests Library 2.27.1
