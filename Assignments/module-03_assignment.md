---
title: 	Catchment-Scale Controls in Logan River Watershed
weight: 1
---
# Module 3 Homework: Catchment-Scale Controls on River Geomorphology

## The Assignment

You will be performing a variety of morphometrics analyses of the Logan River Watershed.

On your website, please make a web-page for module 3 (this is what you'll turn in for Canvas. For the Logan River Watershed (a 10 digit HUC - 1601020303). Your page should have a heading for each of the assignment tasks listed below. I describe the bare minimum you need to include in each task on your page, but you may want to provide additional context. Briefly explain your methods as well. Make sure all questions are answered.

### Assignment Tasks

#### 1 - Map of Logan River Watershed 
1. Make a Location Map (where in Utah is the Logan River Watershed).
2. Make a map of the Logan River Watershed



#### 2 - Longitudinal Profile
1. Produce a **longitudinal profile** graph (distance (meters) vs. elevation (meters)  by pulling a elevation profile of the Logan River from Franklin basin (around  [42.0353,-111.599127](https://goo.gl/maps/qHmhTkBy8H4w7BdK7) down to mouth (around [41.741216, -111.938460](https://goo.gl/maps/vKCdUaMe1im98wTL8)). 
2. What is the **base-level control** of Logan River today (the feature and its elevation)?
3. What was the **base-level control** of the Logan River about 18,000 years ago (feature and elevation)? 
4. What is the **mainstem length** of the  Logan River in kilometers?
5. What is the **concavity** (show calculation)?
6. Label any **knickpoints** (if present) and pose a working hypothesis about the controls?

#### 3 - Catchment Morphometrics

For the Logan River Watershed:
1. What is its **catchment length** in meters? 
2. What is its **catchment area** in square meters and in square kilometers?
3. What is the the **catchment perimeter length** in meters and kilometers?
4. Calculate the **circularity ratio**.
5. Calculate the **elongation ratio**.
6. Calculate the **form factor** of the Logan River Watershed.
7. What is the **catchment relief** of the Logan River Watershed?
8.  What is the **relief ratio** of the Logan River Watershed? 
9.  What is the  **drainage density** of the Logan River perennial drainage network?
10.  What is the **drainage pattern** of the Logan River drainage network?

#### 4 - Stream Order
For the perennial drainage network of the Logan River:
1. What is the **stream order** of the Logan River at its mouth?
2. What is the **stream order** of Temple Fork at its mouth?
3. What is the **stream order** of Beaver Creek?
4. Does the Logan River appear to obey the **Hortonian laws of stream network composition**?



## Resources

### Riverscapes Context 

A [Riverscapes Context Project for HUC 16010203 (Little-Bear Logan)](https://data.riverscapes.xyz/#/PUBLIC_DATA/96c4925e-262f-4726-a6b9-0a57c52639d3) from the [Riverscapes Consortium](http://riverscapes.xyz). - *<i class="fa fa-file-archive-o" aria-hidden="true"></i> 446.87 MB Riverscapes Project viewable in with [RAVE AddIN to ArcGIS 10.X](http://rave.riverscapes.xyz)*. This project has the watershed boundary, DEM and drainage network lines (you can also go find them on other USGS and USDA websites), as well as a ton of additional context. You do not *need* this project to do the homework, but if you plan to do it in ArcGIS 10.6 or later (not ArcGIS Pro), this will help.



### Shapefiles Prepped
There are three files in this [LoganShapefiles+KMZ.zip ](https://usu.instructure.com/files/79946836/download?download_frd=1) <i class="fa fa-file-archive-o" aria-hidden="true"></i> file:
- `LoganRiver_Only.shp` - From the NHD in the context file, this has been clipped to just the mainstem for which you need to extract a profile.
- `Logan_PerrenialNetwork.shp`-  From the NHD in the context file, this has been clipped to just the perrinal portion of the network you'll need for drainage density.
- `LoganWatershed_1601020303.shp` -  From the HUC 8 Watershed, just the HUC 10 for the Logan.

### Google Earth Files
If you want to work in [Google Earth Pro](https://www.google.com/earth/versions/download-thank-you/?usagestats=1), here are the three prepped shapefiles from above in one KMZ:
- [Logan River Watershed Prepped.kmz](https://usu.instructure.com/files/79946820/download?download_frd=1)

### How to:
<div class="row small-up-2 medium-up-2">


  <div class="column">
    <div class="card">


      <div class="card-section">
        <h4>Open Riverscapes Project in GIS with RAVE</h4>
        <div class="responsive-embed"> 

<iframe width="560" height="315" src="https://www.youtube.com/embed/QLboT-YJw-I" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>


</div>
<i class="fa fa-clock-o" aria-hidden="true"></i> < 20 minutes (first 7 all you actually need) <i class="fa fa-youtube-play" aria-hidden="true"></i>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">


      <div class="card-section">
        <h4> Open KMZs in Google Earth Pro and view Profile</h4>
    <div class="responsive-embed">
        	<iframe width="560" height="315" src="https://www.youtube.com/embed/Uhbob-qacso" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        	</div>
        
        <br><br> <i class="fa fa-clock-o" aria-hidden="true"></i> < 4  minutes <i class="fa fa-youtube-play" aria-hidden="true"></i>
        
      </div>
    </div>

  </div>
</div>


------

