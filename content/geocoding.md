---
layout: default
title: Geocoding address data
nav_order: 4
# has_children: true
---

# Geocoding Address Data

What it is why you might want to do it. in this workshop... 


*1*{: .circle .circle-purple} From the workshop data folder, add libraries.csv to your QGIS project. Because it is tabular data (in the form of a .csv, or comma separated value table) and not a spatial layer, nothing will show up on your map. Take a look at the attributes of this table. You'll see there are  street address as well as city and country attributes. We'll use these to geocode this dataset. 

<img src="./images/libraries-att-table_20241227.png" style="width:90%;">

<br>

*2*{: .circle .circle-purple} Install **MMQGIS** plugin from the Plugins Manager. You'll see it adds an entire menu to the top of your screen. Take a look at different options. Choose **Geocode CSV with Web Service**.

<img src="./images/mmqgis-menu_20241227.png" style="width:70%;">

<br>

*3*{: .circle .circle-purple} In the geocoding window that opens, chose the libraries.csv file as your input and leave the outputs as temporary files. The address, city, and country properties will likely auto populate since the column names are - those of inputs. sometimes you do have to manually select which properties. 

Change the web service to **Open Street Map / Nominatim**. Hit apply. There are 22 rows in the library dataset so 22 points should be geocoded and the output csv that indicates what wasn't matched should be empty. 

<img src="./images/geocoding-window_20241227.png" style="width:80%;">

<br>

*4*{: .circle .circle-purple} If you want to shave your geocoded shapefile, simply save from temporary file by exporting it and giving it a proper name and storage location.

<img src="./images/geocoded-libraries_20241227.png" style="width:100%;">

<br>