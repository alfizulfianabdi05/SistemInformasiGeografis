Retrieve Data Geospatial is a way to select / view, the data records of the dbf file from shp file.
ESRI shapefile or usually we know the name shapefile, this is the format of Geospatial data in the form of vectors that are popular. This data format is a non-topological data format that is easy and simple that serves to store data geometric location and attribute information from a geographic data. However, the file is still
yet we can see the results yanpa using helper software like QGIS or Pyhton example.
To read the shapefile using pyhton we can call directly fileshp or could also make sebuh class.
 
SHP is one form of which is located in the shapefile file that stores the data of geometry. In shp files have data such as:
1. Bbox is a boundary box (the coordinates of 4 points) or the coordinates of the boundary points on a map view.
2. Point is the point of coordinates
3. Shapetype the geometry data types that have a standard number assigned by ESRI as No. 1, namely points 2 and 3 which polygons to polyline.

Example Reading the amount of geometry data with python:
1. shapefile import >>
2. >> sf = shapefile.Reader ( "namafile.shp")
3. >> sf.shapes ()
4. >> a = sf.shapes ()
5. >> len (a)
 
