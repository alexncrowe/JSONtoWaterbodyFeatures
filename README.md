# JSONtoWaterbodyFeatures
QGIS plugin that takes an Overpass API query search for bodies of water and creates two geopackages for the linear and areal bodies of water. 

## Import plugin
Download zip folder and save to your QGIS plugins folder.  
## Overpass API
Use [Overpass Turbo] (https://overpass-turbo.eu/) to assist with your search structure. The plugin will classify rivers, canals and streams as linear waterbodies and ponds, reservoirs, lakes as areal waterbodies. Other results will not be created as features. 
## QGIS plugin
Set the json response file as the input. Determine where you want the linear waterbodies and areal waterbodies files saved. Two temporary files will appear in your current QGIS project. 
