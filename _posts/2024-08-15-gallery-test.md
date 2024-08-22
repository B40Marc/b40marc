---
layout: post
title: 'Gallery Practice'
excerpt_separator: <!--more-->
galleries:
  - title: Link to homepage
    image: /assets/images/mount_pierce_lo_res/Crawford_Path_Marker_lo_res.jpg
    url: /
  - title: Link to Hi_Res
    image: /assets/images/mount_pierce_lo_res/Crawford_Path_Marker_lo_res.jpg
    url: /assets/images/mount_pierce_hi_res/Crawford_Path_Marker_hi_res.jpg
date: 2024-08-15
---
<!--more-->
### Photo Gallery Practice
![ Crawford Path Marker ](/assets/images/mount_pierce_hi_res/Crawford_Path_Marker_hi_res.jpg)
{% include image-gallery.html folder="/assets/images/mount_pierce_lo_res" %}
{% include image-gallery.html folder="/assets/images/mount_pierce_hi_res" %}
{% if page.galleries %}{% include image-gallery-index.html %}{% endif %}
