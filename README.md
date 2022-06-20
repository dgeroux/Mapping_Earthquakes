# Mapping_Earthquakes

## Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Tasks
To complete this project, I used a URL for GeoJSON earthquake data from the USGS website and retrieved geographical coordinates and the magnitudes of earthquakes for the last seven days. Then added the data to a map.

## Approach
My approach was to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. I used the Leaflet library to plot the data on a Mapbox map through an API request and created interactivity for the earthquake data.

##### Here's the link to the JavaScript that made it all possible: [Logic](https://github.com/dgeroux/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js)

##### The image below shows every earthquake over the past 7 days ; complete with fault lines, a color coded legend indicating magnitude size, and also varying marker radii that also indicates magnitude size of the earthquakes
![deliverable_one](https://github.com/dgeroux/Mapping_Earthquakes/blob/main/Earthquake_Challenge/deliverable_one.png)

##### The image below added another layer to the map ; major earthquakes over 4.5 magnitude (color coded to be either blue or purple depending on magnitude)
![deliverable_two](https://github.com/dgeroux/Mapping_Earthquakes/blob/main/Earthquake_Challenge/deliverable_two.png)

##### The image below added another map style as a tile layer ; added 'dark' style layer
![deliverable_three](https://github.com/dgeroux/Mapping_Earthquakes/blob/main/Earthquake_Challenge/deliverable_three.png)
