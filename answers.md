1) URL of the WMS:  https://symmetrical-space-fishstick-7vpwrqxggjp9hpr4-8080.app.github.dev/geoserver/ows?service=WMS&version=1.3.0&request=GetCapabilities

2) URL of the WFS GetCapabilities:  https://symmetrical-space-fishstick-7vpwrqxggjp9hpr4-8080.app.github.dev/geoserver/ows?service=WFS&acceptversions=2.0.0&request=GetCapabilities

4) The last layer in the list goes on top

6) URL of Single tile WMS:  https://cautious-waddle-g4vv67v456qf6qj-8080.app.github.dev/geoserver/wms?SERVICE=WMS&VERSION=1.1.1&REQUEST=GetMap&FORMAT=image%2Fpng&TRANSPARENT=true&STYLES&LAYERS=spearfish&exceptions=application%2Fvnd.ogc.se_inimage&SRS=EPSG%3A26713&WIDTH=1900&HEIGHT=1000&BBOX=592926.3576344579%2C4916213.305001386%2C611059.8296028039%2C4925757.237616305

7) URL of tiled request: https://cautious-waddle-g4vv67v456qf6qj-8080.app.github.dev/geoserver/wms?SERVICE=WMS&VERSION=1.1.1&REQUEST=GetMap&FORMAT=image%2Fpng&TRANSPARENT=true&tiled=true&STYLES&LAYERS=spearfish&exceptions=application%2Fvnd.ogc.se_inimage&tilesOrigin=589425.9342365642%2C4913959.224611808&WIDTH=256&HEIGHT=256&SRS=EPSG%3A26713&BBOX=605925.1938559785%2C4913369.21308214%2C608368.4406053978%2C4915812.45983156

size: 256 x 256

8) URL of wmts: 
https://cautious-waddle-g4vv67v456qf6qj-8080.app.github.dev/geoserver/gwc/service/wmts?layer=spearfish&style=&tilematrixset=EPSG%3A4326&Service=WMTS&Request=GetTile&Version=1.0.0&Format=image%2Fpng&TileMatrix=EPSG%3A4326%3A11&TileCol=868&TileRow=518
The level is 11 and some of the unique fields are the Tile Columns and Tile Rows that serve as an index for where this individual tile is located in relationship to the entier image

9) URL of zoomed in image:  
https://cautious-waddle-g4vv67v456qf6qj-8080.app.github.dev/geoserver/gwc/service/wmts?layer=spearfish&style=&tilematrixset=EPSG%3A4326&Service=WMTS&Request=GetTile&Version=1.0.0&Format=image%2Fjpeg&TileMatrix=EPSG%3A4326%3A13&TileCol=3470&TileRow=2072
Tile Column: 3470  Tile Row: 2072

10) URL of zoomed out image: 
https://cautious-waddle-g4vv67v456qf6qj-8080.app.github.dev/geoserver/gwc/service/wmts?layer=spearfish&style=&tilematrixset=EPSG%3A4326&Service=WMTS&Request=GetTile&Version=1.0.0&Format=image%2Fjpeg&TileMatrix=EPSG%3A4326%3A8&TileCol=108&TileRow=64
Tile Column: 108  Tile Row: 64

11) The reason the tile numbers are so different is because they are dependent on the Tile Matrix level (13 in the zoomed in image and 8 in the zoomed out image)

12) The Tile Matrix is the set and zoom level, ranging from 0 (the lowest zoom level) to 21 (the highest level).  In the example above, the Tile Matrix changes from 13 to 8