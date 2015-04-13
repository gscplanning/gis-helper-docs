# Converting a shapefile into a geodatabase feature class

This little tutorial will walk you through how to convert a shapefile into a geodatabase feature class using ArcGIS. This will be broken into two larger parts:

1. Creating a geodatabase
2. Converting a shapefile into a feature class

By the end, you should be able to work with your layer as a feature class in a geodatabase.

## Creating a geodatabase

When using a geodatabase it's important to keep in mind that the geodatabase itself is just a container for data. While it has special functionality for spatial data, it serves the same purpose as any other file folder on your computer. In fact, if you look at a geodatabase outside of ArcCatalog or ArcMap it will just look like a folder on your computer.

The data that are stored in a geodatabase are called *feature classes*. These are equivalent to shapefiles. What you'll really be doing through this process is converting a shapefile to a feature class that resides in a geodatabase. But before you can do that conversion, you need a place, a geodatabase, for your feature class to be stored. In short, you need to create a geodatabase:

1. In ArcMap, open up the ArcCatalog pane. You can access this from the toolbar:<br>
![](http://i1368.photobucket.com/albums/ag172/gscplanning/shp2gdb/catalog1_zpsvqaybzkr.jpg)
2. In the ArcCatalog pane, navigate to a folder where you want to store your geodatabase. In this example, I'll be using `C:\temp`, but you can use whichever folder you'd like.<br>![](http://i1368.photobucket.com/albums/ag172/gscplanning/shp2gdb/catalog2_zpssjdt66gm.jpg)
3. Right-click on the folder where you want to store your geodatabase, navigate to **New>File Geodatabase**. Left-click **File Geodatabase**<br>![](http://i1368.photobucket.com/albums/ag172/gscplanning/shp2gdb/catalog3_zpsfuqq3n14.jpg)
4. blerg




