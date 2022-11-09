# Mapping_Earthquakes

### Overview

In this project, we are creating an earthquake map to help viewers visualize the areas where earthquakes have occured in the last 7 days. We do this using JavaScript, the Leaflet library and MapBox APIs. We used realtime earthquake notifications from [USGS](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php).  
In the maps, you may
- pick from various basemaps: 
  * Streetmap 
  * Satellite Map
  * Dark view Map
  
- choose between various visualization features: 
  * Tectonic Plates
  * Earthquakes
  * Major Earthquakes  
  
 A legend is also provided to ensure your viewing experience gives you the best understanding of our data.  
 
  ---
 
 ### Preview: 
 
 Let us take a look at some of these features:
 
 ![tectonicPlates](https://github.com/SoumyaAbraham/Mapping_Earthquakes/blob/main/Screenshots/tectonic%20plates.png)
 
At one glance, we notice the *streetmaps basemap*, a layer indicating the tectonic plates and the circular markers representing each earthquake occurence. 
 1. The options provided to you in the top-right corner allows you to pick between 3 types of basemaps. In this view, notice that *Earthquakes, Tectonic Plates and Major Earthquakes* have been selected.
 2. The legend on the bottom-right corner helps in understanding the color-coded circular markers for each earthquake by magnitude.
 
 
![dark_map](https://github.com/SoumyaAbraham/Mapping_Earthquakes/blob/main/Screenshots/dark_map.png)

In this case, all the layers are the same. The only difference is the use of the *dark-themed basemap*.

 
![major_eathquakes](https://github.com/SoumyaAbraham/Mapping_Earthquakes/blob/main/Screenshots/major%20earthquakes.png)

Notice here, there are significantly less earthquake markers. This is because we have only selected the *Major Earthquakes* option.
You can also see the *satellite basemap* is being used here.

---

You can view the codes for the project [here](https://github.com/SoumyaAbraham/Mapping_Earthquakes/tree/main/Earthquake_Challenge)   

The links for data collected for this project can be found below.
* [All earthquakes in the past 7 days](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
* [Major earthquakes in the past 7 days](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)
* [Tectonic Plates](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)





