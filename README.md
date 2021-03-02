# leaflet-gsheets

URL for THIS repository: [https://franklinassoc.github.io/test-leaflet-gsheets/](https://franklinassoc.github.io/test-leaflet-gsheets/)

Example repository for a project using [Leaflet](https://leafletjs.com/) and [Tabletop.js](https://github.com/jsoma/tabletop) to display a web map that automatically pulls data from two simple Google Sheets tables (as well as preload from JSON files for speed and in case the Googlle API changes). Sidebar created using [leaflet-sidebar-v2](https://github.com/nickpeihl/leaflet-sidebar-v2).

To get started, fork this repo and use the .CSV files in the data-sources folder (they are missing) as examples to create the Google Sheets data source.

The resultant map by Chris A. can be seen here: [https://rdrn.me/leaflet-gsheets/leaflet-gsheets.html](https://rdrn.me/leaflet-gsheets/leaflet-gsheets.html)

Chris explained the process in more length in his blog post here: [Leaflet maps with data from Google Sheets](https://rdrn.me/leaflet-maps-google-sheets/).

## Folium and gspread

Chris did another version (code in the [folium-gspread](https://github.com/carderne/leaflet-gsheets/tree/master/folium-gspread) folder) recreating this using only Python and the [Folium](https://github.com/python-visualization/folium) library. This requires a server instance running to update the map, however. The output map is identical to the one created above. Chris explained this version in a blog post: [A workflow for Python mapping with automatic updating](https://rdrn.me/python-mapping-automatic-updating/) 
