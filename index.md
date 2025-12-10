---
layout: default
title: Introduction
nav_order: 1
has_children: true
---
# Plugins in QGIS

This workshop is meant to extend basic knowledge of QGIS by exploring common plugins. Familiarity of the QGIS is therefore a prerequisite. By the end of this workshop, participants will be able to use plugins to 

- Access dynamic basemaps hosted on web servers
- Query and download Open Street Map (OSM) data 
- Geocode address data from a spreadsheet, and
- Create an interactive webmap from a QGIS project (see below for example)



<iframe src="./content/qgis2web/index.html" style="width:100%; height:630px; border:none;"> </iframe>





## Before the Workshop!!

1. **Review our Introduction to Mapmaking with QGIS** Please note that the fundamental skills and concepts pertaining to spatial data, map types, and the QGIS interface will *not be* covered during this workshop. Therefore, prior to the workshop date, please review our *[Introduction to Mapmaking with QGIS](https://ubc-library-rc.github.io/gis-mapping-intro/)*. **Familiarity with the QGIS interface *is prerequisite* for this workshop.**

2. **Make sure you've downloaded QGIS** QGIS can be downloaded from [qgis.org's Downloads page](https://qgis.org/en/site/forusers/download.html). In most cases, you'll want to download and install the **Long term release** instead of the latest release - currently **QGIS 3.40.4 'Bratislava'**. This will give you most of the functionality you'll need without encountering the software bugs of newly released versions. [See here](https://ubc-library-rc.github.io/gis-intro-qgis/content/installing-qgis.html) for further guidance.


3. **Download and unzip the workshop data folder** below. Download it to a folder on your physical computer, such as Desktop or Downloads, _not_ OneDrive.

[Download Workshop Data](./qgis-plugins-workshop.zip){: .btn .btn-blue }

<!-- > - **Familiarity with the QGIS interface is prerequisite for this workshop.** Additionall, if you are new to QGISCheck out the Research Commons' [Map Production with QGIS](https://ubc-library-rc.github.io/gis-intro-qgis/) and [Tools and Workflows in QGIS](https://ubc-library-rc.github.io/gis-tools-workflows/) workshops if you are new to GIS, or your background is in Esri ArcGIS products. You can also browse the QGIS Documentation's [Getting Started](https://docs.qgis.org/3.34/en/docs/user_manual/introduction/getting_started.html) for a refresher. Although this workshop will entail making a web map powered by Leaflet, no prior knowledge of coding or webmapping is necessary. Indeed, the QGIS plugin you will be introduced to specifically circumvents the need to build a web map with code. However, understanding the way Leaflet works to power a web map may make your experience more interesting. If you'd like a gentle introduction to Leaflet, check out the Research Commons' workshop: [Introduction to webmapping with Leaflet](https://ubc-library-rc.github.io/gis-intro-leaflet/). -->

<br>


---
#### GIS Resources at UBC:
- General Informational website for all things UBC GIS: [gis.ubc.ca](http://gis.ubc.ca/)
- UBC Library's guide for finding and working with GIS resources: [guides.library.ubc.ca/gis](http://guides.library.ubc.ca/gis)
- UBC's GIS Slack (create your own channel or lurk!): [ubcgis.slack.com](https://ubcgis.slack.com/)
- Archive of all [Research Commons workshops](https://ubc-library-rc.github.io/)
- Research Commons [Events Calender](https://researchcommons.library.ubc.ca/workshops/)
- Contact UBC Library’s Geospatial team: `library.gis@ubc.ca`
- Schedule a 1:1 consult with the geospatial team [here](https://libcal.library.ubc.ca/appointments/research_commons#s-lc-public-pt)

<p style="margin-top:90px"></p>
<p style="color:grey; font-size:11px">This workshop was authored by <a href="https://geog.ubc.ca/profile/lily-crandall-oral/" target="_blank">Lily Demet</a> and reviewed by Alex Alisauskas.</p>
