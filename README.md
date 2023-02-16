
## Tsunami-Scenarios
### Exploring Tsunami Evacuation Times/Scenarios on the Oregon Coast

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

## Potential Problems/Considerations:

Accounting for random variables 
		(debris, flooding severity, trees being down, etc)

How to simulate flooding via Python

Machine Learning Model?

Speed, mode of transportation in regards to evac. times. 

## Useful Links

UO Infographics lab research on evacuation routes
https://infographics.uoregon.edu/projects/tsunami-evacuation-dogami/

NANOOS
https://nvs.nanoos.org/TsunamiEvac

Tsunami inundation maps
https://www.oregongeology.org/tsuclearinghouse/pubs-inumaps.htm

“Beat the Wave”
https://www.oregongeology.org/tsuclearinghouse/beatthewave.htm

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