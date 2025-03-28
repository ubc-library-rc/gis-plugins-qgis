---
layout: default
title: Adding Basemaps
nav_order: 2
---
# Add basemaps with QuickMapServices plugin

A basemap is helpful to give spatial context to your data as you work. One way to add a basemap is through a plugin. Two popular plugins for accessing basemaps are **QuickMapServices** and **OpenLayers**. Installing either of these plugins will connect you to a host of different basemaps which you can browse and add to your project all within your QGIS interface. This workshop will use **QuickMapServices**. 

<br>

*1*{: .circle .circle-purple}
To access basemaps, we'll first install the QuickMapServices plugin. Click on the **Plugin** menu at the top of your screen and select **Manage and Install Plugins...**   

<img src="./images/install-plugin_20240404.jpg" style="width:100%"> 
   
   <br><br>
*2*{: .circle .circle-purple} In the dialogue box that opens, select **All** as a search category on the left and then type "QuickMapServices". Install the plugin and close the dialogue box.    

<img src="./images/quickmapservices_20240404.png" style="width:100%">
    

<br>
  
*3*{: .circle .circle-purple} 
Now, in the main QGIS interface, go to the **Web** menu at the top of your screen. You should see the QuickMapServices plugin. Hover over it until a drop-down menu appears. Go down to "Settings". In the plugin's settings, go to the "More services" tab and click "Get contributed pack." Click **save** to close settings and return to the **Web** menu. This time when you hover over the QuickMapServices plugin you will see an array of basemap options. 

<img src="./images/get-contributed-pack.png" style="width:70%">
    
<br>
  
*4*{: .circle .circle-purple} 
Try adding different basemaps such Esri Sattelite or OSM Standard. Like QGIS, [Open Street Map (OSM)](https://www.openstreetmap.org/about) is open source and user developed. 

![add basemap](./images/add-basemap_20240607.png)
    

<br>
  
Use the zoom tools <img src="./images/zoom-tools.png" style="width:30%"> located in the toolbar to zoom to see each basemap in detail. Hide a basemap at any time by unchecking the box beside it in the Layers panel. Remove a basemap at anytime by right clicking the layer and selecting "remove."
    

![remove basemap](./images/remove-basemap_20240607.png)

<br>


Sometimes when you re-open a QGIS project basemaps previously loaded will turn up blank. Try right-clicking the basemap in your Layers Panel and zooming to it. Otherwise, simply re-add the basemap from the Web menu at the top of your screen. 
{: .note}

---
#### Resources for further exploration

- Explore other [popular QGIS Plugins](https://plugins.qgis.org/plugins/popular/) or browse plugins through [keyword tags](https://plugins.qgis.org/plugins/)

- Many basemaps that are hosted by web services are tile layers. This means they are a collection of static images ([map tiles](https://ubc-library-rc.github.io/gis-intro-leaflet/content/leaflet-basemap.html)) that are loaded as you zoom in and out on your screen. Therefore, you can also connect a basemap as an XYZ tile connection. [This video](https://www.youtube.com/watch?v=ht7tgmuwkpA) demonstrates how. 
 
- If you find web-based maps interesting, check out the Research Commons' [Leaflet Workshop](https://ubc-library-rc.github.io/gis-intro-leaflet/) or [Introduction to web mapping with Mapbox](https://ubc-library-rc.github.io/intro-mapbox/)


