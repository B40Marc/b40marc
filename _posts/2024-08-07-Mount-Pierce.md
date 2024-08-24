---
layout: post
title: "Mount Pierce"

galleries:
  - title: Crawford Path Marker 
    image: /assets/images/mount_pierce_lo_res/Crawford_Path_Marker_lo_res.jpg
    url: /assets/images/mount_pierce_hi_res/Crawford_Path_Marker_hi_res.jpg
  - title: Gibbs Falls
    image: /assets/images/mount_pierce_lo_res/Gibbs_Falls_lo_res.jpg
    url: /assets/images/mount_pierce_hi_res/Gibbs_Falls_hi_res.jpg
  - title: Mount Pierce Summit! 
    image: /assets/images/mount_pierce_lo_res/Mount_Pierce_Summit_lo_res.jpg
    url: /assets/images/mount_pierce_hi_res/Mount_Pierce_Summit_hi_res.jpg
date: 2024-08-07
---

### My Hike of Mount Pierce




{% leaflet_map { "center": [44.224038, -71.389107],
                 "zoom" : 13, 
     "providerBasemap": "OpenTopoMap" } %}

    {% leaflet_marker {"latitude" : 44.226872,
                       "longitude" : -71.365724,
    "popupContent": "Mount Pierce ... 4312 ft"}
  %}

{% leaflet_geojson "/assets/geojson/Mount_Pierce_cmpt.geojson" %}

{% endleaflet_map %}

Mount Pierce is the 27th highest of the 48 four thousand footers recognized by the Appalachian Mountain Club (in descending order from number one Mount Washington).   

Mount Pierce is my 27th mountain climbed of the forty-eight. Mount Pierce is 4312 feet.  

Today was a wonderfully beautiful day, in a week of not so wonderful weather. A minor cold front pushed in Tuesday night and dropped the heat, humidity, and rain from the forecast. Later, this week the remnants of tropical storm Debby will encroach. Not fun, being above 4000' with lightning and thunderboomers. But, today was sunny, mid-60's, high scattered clouds. Just a perfect hiking day!  

Most of the hike was on the Crawford path, one of the oldest in the Whites. This was perhaps the busiest path I've encountered, save for Franconia ridge, on my hikes. A Wednesday, mid-week day and crossed about a hundred hikers. And then there were the trail runners, at least six of them. One guy passed me both ascent and decent, before I'd made two thirds of my climb. On the way down he was running pell-mell full speed like a jack rabbit. They are a different breed. I just don't get it.  
{% if page.galleries %}{% include image-gallery-index.html %}{% endif %}
