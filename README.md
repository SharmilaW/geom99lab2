This geojson file was created using
[geojson.io](https://geojson.io/#map=15.11/44.3416/-78.744033 )

# geom99lab2
BUG Report
For the base map, the code used is 
const map = new Map({
basemap: "arcgis-topographic"
});
But only the hill shade map is loaded in the output as we do not have access to the ArcGIS base map.

