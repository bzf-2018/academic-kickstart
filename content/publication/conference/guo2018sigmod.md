---
title: "POIsam An Efficient Object Selection System for Interactive and Visualized Exploration of Geospatial Data"
authors:
- Tao Guo
- Mingzhao Li
- Peishan Li
- admin
- Gao Cong

publication_types: ["1"]
publication: In *the 2018 International Conference on Management of Data (SIGMOD)*
publication_short: In *SIGMOD*
publishDate: "2018-06-10"

abstract: In this demonstration we present POIsam, a visualization system supporting the following desirable features - representativeness, visibility constraint, zooming consistency, and panning consistency. The first two constraints aim to efficiently select a small set of representative objects from the current region of user’s interest, and any two selected objects should not be too close to each other for users to distinguish in the limited space of a screen. One unique feature of POISam is that any similarity metrics can be plugged into POISam to meet the user’s specific needs in different scenarios. The latter two consistencies are fundamental challenges to efficiently update the selection result w.r.t. user’s zoom in, zoom out and panning operations when they interact with the map. POISam drops a common assumption from all previous work, i.e. the zoom levels and region cells are pre-defined and indexed, and objects are selected from such region cells at a particular zoom level rather than from user’s current region of interest which in most cases do not correspond to the pre-defined cells. It results in extra challenge as we need to do object selection via online computation. To our best knowledge, this is the first system that is able to meet all the four features to achieve an interactive visualization map exploration system.


#tags:
#- Source Themes
featured: true

links:
- name: Demo
  url: http://www.google.com/url?q=http%3A%2F%2F18.217.173.184%2F&sa=D&sntz=1&usg=AFQjCNG_KC21RZZdMgKh6SvJ08OYMkBUfA
url_pdf: https://dl.acm.org/citation.cfm?id=3193549

---