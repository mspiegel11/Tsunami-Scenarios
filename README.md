
## Tsunami-Scenarios

### Exploring Tsunami Evacuation Times/Scenarios on the Oregon Coast
## names: Max Spiegel, Isaac Bell Anna Anton

### Summary: Exploring potenial Tsunami Evacuation Times/Scenarios at different cities along the Oregon Coast.

=======

## Questions to explore
#### What locations have the highest evacuation time to ‘tsunami-safe’ areas?

#### How would these travel times be affected by flooding, debris, road blockages, etc?

#### What would the change in evacuation time look like based on tsunami/earthquake severity?

## Potential Data Sources

Elevation Data (DEM)

OR roads layer

OR coast shapefile

Attribute data

City locations

Emergency Service Locations

Populated vs Unpopulated areas

Census Data

## Potential Problems/Considerations:

Accounting for random variables 
		(debris, flooding severity, trees being down, etc)

How to simulate flooding via Python

Machine Learning Model?

Speed, mode of transportation in regards to evac. times. 

The population of each town and compare that to how many evacuation sources there are.

## Useful Links

UO Infographics lab research on evacuation routes
https://infographics.uoregon.edu/projects/tsunami-evacuation-dogami/

NANOOS
https://nvs.nanoos.org/TsunamiEvac

Tsunami inundation maps
https://www.oregongeology.org/tsuclearinghouse/pubs-inumaps.htm

“Beat the Wave”
https://www.oregongeology.org/tsuclearinghouse/beatthewave.htm

DOGAMI: Tsunami inundation scenarios for Oregon
https://www.oregongeology.org/pubs/ofr/p-O-13-19.htm

## Python Libraries we need:

numpy

geopandas

osmnx

networkkx

os

shapely.geometry

matplotlib.pyplot

folium

rasterio

elevation (https://pypi.org/project/elevation/)
### Misc Thoughts/Process

use omnx to download and create road networks for study areas (Florence, Seaside and Coos Bay)

merge this with elevation data from elevation python library

reference oregon maps to see what areas are considered 'safe' from tsunami within this region

use this information/numpy to calcualte travel times from within the bounding box to these regions

plot that iformation, maybe try to use random number generatior to create more variabeles to see how that affects travel time

figure out a way to use this code for the entire coast (if possible)

## Expected Outcomes

We would expect to see evacuation times directly correlated to elevation. Areas closer to sea level likely have longer evacuation times than higher-elevation ones. Our initial results can be expected to be similar to DOGAMI's 'Beat the Wave' dataset, which maps the necessary speed for tsunami evacuation in each of the communities we are studying.
