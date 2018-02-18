# Mapbox-Project
Map created using Mapbox (https://www.mapbox.com/)

Goal 1 - Add Display a popup on click (https://www.mapbox.com/mapbox-gl-js/example/popup-on-click/): When a user clicks on one of the points in the map, a popup will appear showing this information:

   "Type": "Venue",
    "Name": "Sala Apolo",
    "Address": "Carrer Nou de la Rambla 113, 08004 Barcelona",
    "Atmosphere": "Concerts - Club",
    "Web": "https://www.sala-apolo.com/",
    "Facebook": "https://www.facebook.com/SalaApolo/"
    
Coming from the JsonGeo file already present as a dataset into Mapbox:

{
  "type": "Feature",
  "properties": {
    "Type": "Venue",
    "Name": "Sala Apolo",
    "Address": "Carrer Nou de la Rambla 113, 08004 Barcelona",
    "Atmosphere": "Concerts - Club",
    "Web": "https://www.sala-apolo.com/",
    "Facebook": "https://www.facebook.com/SalaApolo/"
  },
  "geometry": {
    "coordinates": [
      2.169531,
      41.374409
    ],
    "type": "Point"
  }
}



Goal 2 - Add Show and hide layers (https://www.mapbox.com/mapbox-gl-js/example/toggle-layers/)

Show the 5 different types of “Type” on the map (Venus, Pop-up venue, Festival, Record shop, Conference) so that users can select which type they want to see on the map.

Automatically when a user opens the map for the first time, all the different types are selected and appear on the map

Show them on the upper right corner, right under the zoom commands (smaller than on the example in the link above)
