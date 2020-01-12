# Mapping Earthquakes
Use JavaScript's Leaflet library along with the Mapbox API to create visualizations of earthquake data from the U.S. Geological Survey.

## Module Overview
In this module, you will use the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake will be visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake will have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.

## Project Overview
In this challenge, you’ll add a third map style as an additional tile layer. You'll also add tectonic plate GeoJSON data to the map to illustrate the relationship between the location and frequency of seismic activity and tectonic plates.

The goals for this challenge are to:
1. Use d3.json() to get tectonic plate data and add the data using the L.geoJSON() layer.
2. Style the tectonic plate LineString data to stand out on the map.
3. Add the tectonic plate data as an overlay with the earthquake data.
4. Add a third map style to allow the user to select from three different maps.

## Resources

- Software: Visual Studio Code 1.39.0
- Languages: JavaScript, HTML, CSS, Bootstrap
- Libraries: Leaflet, D3, Mapbox
- Data Sources:
  1. Earthquakes: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
  2. Tectonic plates: https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json

## App Preview

Here is a preview of what the web app looks like once all the new map features have been created and enabled:

![alt text](https://github.com/jbtrahin/Mapping_Earthquakes/blob/Earthquake_Challenge/Earthquake_Challenge/leaflet_app_preview.png)
