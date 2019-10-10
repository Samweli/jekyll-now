---
layout: post
comments: true
title: Visualizing Dar es salaam City Drone Imagery
published: true
---


![](https://raw.githubusercontent.com/samweli/jekyll-now/master/images/dar-drone-imagery-viz.png)

_Drone Imagery Map_

## Visualizing Dar es salaam drone imagery
At the end of 2017 The World Bank Tanzania helped in collecting drone imagery in Dar es salaam as per the request of 
[DART](https://www.dart.go.tz/) (Dar Rapid Transit).

The activity covered all areas that are nearby all the planned BRT (Bus Rapid Transit) phases.

After successful imagery data collection, next it was required to create data visualization, 
the raw data was too large to load in normal computer, it took long time to view it, also the data formart (geotiff) requires special GIS applications to access and view, this constrained all user to first install those applications. 

Hence other tool was needed to be built in order to simplify data access and use.

As part of the World Bank Tanzania team which supported DART to collect the data I was tasked to create visualization for the drone imagery.

I decided to use [Mapbox GL](https://docs.mapbox.com/mapbox-gl-js/overview/) to build the web map which shows the imagery.

The result was a high perfomance and easily accessible web map. You can view it [here](http://brt-viz.herokuapp.com/)
