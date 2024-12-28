---
layout: default
title: Exploring your webmap
nav_order: 3
parent: Webmapping with QGIS
---
# Exploring your webmap

From your computer, navigate to the workshop folder. inside should now be a new folder called qgis2web followed by the date. open this folder. 

inside are many subfolders 

<img src="./images/subfolders_20241228.png" style="width:70%">

> - **css** is the cascading style sheets responsible for the sybology of or map layers. leaflet. 
> - **data** is your data layers
> - **images** any images
> - **js** is the javascript - leaflet - code library powering the map - interactivity etc.
> - **legend** contains icons of legend
> - **markers** is empty because you have no stand alone drop pins on your map
> - **webfonts** contains font families of text

There is also an `index.html` document. html is language read by web browsers. either double-click this file or right-click and choose to open with a web browser of your choice. 

Your map should load in a web browser
<img src="./images/webmap-in-browser_20241228.png" style="width:100%">

notice the file path in the search bar. 

try interactive ness
- check and uncheck layer visibliyt in list
- collapse and expand list
- zoom in and zoom out; pan around
- click on different points

notice attribution at bottom right

If you want to change anything, you can always return to qgis and re-run. new output folder. though date and timestamped, i find it helpful to delete or discard old folders. 



<!-- ## Codeside view

You can also explore - as code - and adjust things from that end. lets take a look at codeside view of html document, just for fun. again, leaflet workshop will  delve more into this.  -->

