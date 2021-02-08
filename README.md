#GarminCustomMap

GarminCustomMap plugin for QGIS (2.0 and later) exports the current map canvas to a .kmz file, which is compatible with Garmin handheld GPS units supporting  Garmin's Custom Maps format.

Maps styled in QGIS can be used as raster maps on the compatible Garmin GPS units. 

WHAT IS GARMIN CUSTOM MAP .KMZ

A Garmin Custom Map (.kmz file) is a .zip file containing one or more jpg-images (tiles), and the georeference infomation in a text file (doc.kml).
Each .jpg is limited to 1 megapixel (e.g. 1024 x 1024 pixel or 2048 x 512 pixel) and file size should be less than 3MB. 

Note: Number of Custom Map jpgs (tiles in .kmz-file) on a GPS unit is usually limited to 100 jpgs - across all Custom Maps on the unit. However, newer Garmin GPS units (Montana, Oregon 6x0, and GPSMAP 64) have a limit of 500 tiles on the device in total.

OPTIONS

Drawing speed of the map on your GPS unit is affected by the file size of the jpgs. That can be controlled by tile size (number of rows and columns) and JPG compression (quality). 

With the "Opimize tile size automatically" flag checked (on by default) the tile size will be adjusted to the short side of the map to produce the minimum number of tiles for the map area. 

When "Skip production of empty tiles" is checked (default), tiles which are entirely white (white is the default background color) are not produced in order to minimize the number of tiles. 

TRANSFER .KMZ TO UNIT
Copy .kmz file into directory /Garmin/Custommaps on device internal memory or on memory card 

News map are visible by default. Visibility can be changed: On Map View press Menu > Setup map > Select Map. Or Setup > Map > Select Map.

COMPATIBLE Garmin device series are:
Alpha, Astro, Dakota, Oregon, Colorado, GPSMAP 62 series, GPSMAP 64 series, GPSMAP 78 series, Edge 800, Montana, Rino, eTrex® 20 and 30

For more technical details and limitations regarding Garmin Custom Maps see:
https://forums.garmin.com/showthread.php?t=2646

For more information on Garmin Custom Maps and compatible GPS units see:
http://www.garmin.com/us/products/onthetrail/custommaps

(C) Norwegian Institue for Nature Research (NINA), http://www.nina.no
Stefan Blumentrath (email: stefan dot blumentrath at nina dot no) 
