# BME-450-Project-3

Code Link: https://github.com/SamEF99/BME-450-Project-3/blob/master/BME%20450%20Project%20%233.ipynb

# Problem Statement:

For this project, we need to analyze data for earthquake magnitude and location on the boundaries of the Juan De Fuca Plate. We first need to download data from the USGS website for 2.5+ magnitude eathquakes from January 1st 2010 to March 1st 2020, and for only April 2015. We then need to plot earthquake magnitude over time for the ten year period, and the location of earthquakes for both time periods over a map of the area. We also need to adjust the radius of the scatter glyphs in proportion to the magnitude of each earthquake. We then need to analyze this map data in several ways, including finding why April 2015 was significant. We finally need to identify which areas are divergent and transform boundaries, mark them on the map, and explain the trends we see in these areas. 

# The Code: 

The code starts by pulling data from Github for the ten year span CSV. We then append that data to chosen variables, calling to columns in the dataset. We use those variables to plot the earthquake magnitude over time. Next, we use Geoviews to plot the earthquake location over time. We create a set of datapoints from the latitude and longitude data, and plot that over a Carto Light map from the Geoviews tile sources. We also set the size of the scatter glyphs to be dependent on the size of the datapoint, and outline them in grey to distinguish different points. We repeat the same process again for the CSV file from April 2015.

# Results:

![](BME450_Project_3_Fig_1.PNG)

![](BME450_Project_3_Fig_2.PNG)

![](BME450_Project_3_Fig_3.PNG)

# Questions:
