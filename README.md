# Project2: GeoWeb APP

ENGO 651 - Advanced Geospatial Topics

## Overview:
This website is an assignment for Advanced Geospatial Topics (ENGO 651) by group 6. We created a web mapping application for building permits in Calgary, Canada, which is taken from the Open Calgary API dataset. Users can find all building permits on the map by selecting the issue date range they like. Moreover, some useful information, such as contractor name and community name, of any building permit exists on the pop-up content of the marker that represents the specific building permit. To make the map visually appealing, we handled the problem of overlapping markers and made a cluster of the neighboring markers on the map.   


## Libraries required to install:
- Flask 
- requests <br>
You can find both libraries in the `requirements.txt` and install them by running this command `pip3 install -r requirements.txt` in the terminal window.

## Tools and Resources used:
- HTML 5
- CSS
- Python flask 
- Javascript
- [Leaflet](https://leafletjs.com/)
- [GeoJSON](https://leafletjs.com/examples/geojson/)
- [Open Calgary API dataset](https://data.calgary.ca/Business-and-Economic-Activity/Building-Permits/c2es-76ed)



## what’s contained in each file:
- `application.py`: is responsible for python flask coding and getting JSON data from Open Calgary API dataset and then passes it to the `building_permit_search.html` file.
- `templates/building_permit_search.html`: has the structure of the webpage and all links of Leaflet code.   
- `static/styles/building_permit_search.css`: this is a specified style sheet file for `building_permit_search.html` file.
- `static/js/building_permit_search.js`: creating Leaflet map and date range widget algorithm are located in this file.
- `static/js/building_permits_after_searching.js`: all algorithms after searching, including adding markers to the map, handling overlapping markers, and markers clustering, exists in this file.








