# Nigeria Population Density 2020
 
Status: In progress

## Overview
The aim of this project is to visualize the population density of states in Nigeria using a choropleth map. You can find the live version of the final web map [here](https://controleo.github.io/Nigeria-Population-Density-Map-2020/).
## Data Source
+ The population dataset was obtained from WorldPop. It records the spatial distribution of the Nigerian population in 2020, with the country's total adjusted to match the corresponding UNPD estimate.

+ The state boundary data was obtained from Diva-GIS.
## Stack
- QGIS Desktop software

- The `qgis2web` plugin was used for web mapping
## Result and Visualization 
Using the method of zonal statistics, the sum of population data points within each state boundary was calculated and stored in a new column. The map was further classified into 4 classes of unequal intervals to capture major data shifts. 

The population data for each state can be viewed by hovering over the state of interest. The map can be filtered by state (s) using the filter panel on the top right. The navigation buttons on the top left can be used to zoom in and out, measure the distance between points, and search for locations. 

The colour choice was influenced by the country's flag colours; Green and White.
## External Links
Here are tutorial videos from my YouTube channel:

[How to download population data from WorldPop](https://youtu.be/7D2n1K4Txgs)

[How to download boundary data from DivaGIS](https://youtu.be/-zEKCEFxMKc)

[How to perform zonal statistics](https://youtu.be/FJZLO1Yqes8)

[How to make a choropleth map](https://youtu.be/FebVhINeCQE)

[How to create a web map](https://youtu.be/JEzKWHdi49o)
