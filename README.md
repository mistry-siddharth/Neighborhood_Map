# Neighborhood_Map
The objective of this project is to develop a single page application featuring a map of a neighborhood, and writing a manageable code using frameworks, libraries and APIs. Functionality was then added to the map to highlight certain favorite locations, and display extra information (e.g. name of place, type of place, address, images, opertion hours, etc.) for those locations using third-party API (e.g. Foursquare). Also information was presented such that those locations can be browsed in different ways (e.g. selecting directly on the map or searching for the location in a search bar) and the result to be highlighted on the map. 

## Installation
### Dependencies
- [Fenix web server](http://fenixwebserver.com/)
- [Knockout JS](http://knockoutjs.com/downloads/knockout-3.4.2.js)
### To run the application follow the following steps:
1. Download the GitHub zip file or clone the repository onto your local machine.
2. Use Fenix web server to create an ad-hoc static web server.
3. Select the directory in Fenix where .html is placed.
4. Hit run!
  #### Alternatively:
1. Download the GitHub zip file or clone the repository onto your local machine.
2. Execute the .html file or open that .html in a browser.

## Tools and Concepts
- Knockout JS framework
  - This frameowork is based on MVVM (Model View ViewModel) framework.
- Google Maps API
  - To display map and utilize other features of the map, such as using pins to highlight a location and perform operations on that.
- Foursquare API
  - This API was used to retreive more information about a location and displaying it in an info window.

## App Functionality
- Created a map for Richmond, VA and displays a few restaurants in the area.
- Notifies users if an error occurs while loading Google Maps and retreiving data from foursquare API.
- Collects data using Google Maps APIs and foursquare API.
- Map automatically adapts to different viewports, adjusts bounds and zooms to accommodate all markers.
- Menu opens and closes with the hamburger icon.
- List of venues can be filtered by keywords in the Search bar. Filtering the list also filters respective map markers.
- Click on item in list view changes marker's color and animates it, and opens infowindow with information in it.
- Clicking on marker changes icon color, and animation.
- Clicking on map or on close button of info window closes the info window and the marker returns to default state (no animation and default color).
