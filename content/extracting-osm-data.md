---
layout: default
title: Extracting OSM Data
nav_order: 3
---
# Extracting OSM Data
What this means, why its helpful, what plugin we'll use.

<br>

*1*{: .circle .circle-purple} Add the **OSM Standard** basemap to project and drag beneath your other data layers. Zoom to `van-shoreline`.

    
<br>

*2*{: .circle .circle-purple} From the **Plugins** menu at the top of your screen, navigate to “Manage and Install Plugins…” In the Plugins dialogue box that opens, first go to Settings and enable experimental and deprecated plugins. Return back to All and search “QuickOSM.” Install the plugin and close the dialogue box. 
    

<br>
*3*{: .circle .circle-purple} Now click on the **Vector** menu at the top of your screen and go to "QuickOSM." (Note you can also search for the tool in your processing toolbox.)

![open quick osm](./images/open-quick-osm_20241215.png)
    
<br> 

*4*{: .circle .circle-purple} 
In the dialogue box that opens, you can choose what attributes to query and download, as well as the geographic extent to download in. 

Depending on what OSM data you're downloading, you'll want to set the  from OSM on what data you're downloading, you may not want to download for the entire world or city. For instance, buildings or roads. good to start with smaller extent. For today's workshop we'll download artwork, specificaly murals, within the extent of vancouver's shoreline. 

So, input the relevent parameters.

![quick osm query](./images/quick-osm-query.png)
    

If you go to the x page, you can see how its searching and where its saving. lets keep it as a temporary file for now. 

Run Query. 
    
<br>

*5*{: .circle .circle-purple} Drag the output file `artwork_type_mural` to the top and chage the symbology if necessary to differentiate it from your public-art layer from the city of vancouver. 

![artwork type mural](./images/artwork-type-mural_20241215.png)

Open attribute table to see whats there. 

save file to project workshop data folder as  `osm-murals`. 

Remember  - murals in vancouver can update every year - dont take this data as fact. 