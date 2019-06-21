---
title: "Efficient Selection of Geospatial Data on Maps for Interactive and Visualized Exploration"
authors:
- Tao Guo
- Kaiyu Feng
- Gao Cong
- admin

publication_types: ["1"]
publication: In *the 2018 International Conference on Management of Data (SIGMOD)*
publication_short: In *SIGMOD*
publishDate: "2018-06-10"

abstract: With the proliferation of mobile devices, large collections of geospatial data are becoming available, such as geo-tagged photos. Map rendering systems play an important role in presenting such large geospatial datasets to end users. We propose that such systems should support the following desirable features - representativeness, visibility constraint, zooming consistency, and panning consistency. The first two constraints are fundamental challenges to a map exploration system, which aims to efficiently select a small set of representative objects from the current region of user’s interest, and any two selected objects should not be too close to each other for users to distinguish in the limited space of a screen. We formalize it as the Spatial Object Selection (sos) problem, prove that it is an NP-hard problem, and develop a novel approximation algorithm with performance guarantees. To further support interactive exploration of geospatial data on maps, we propose the Interactive sos (isos) problem, in which we enrich the sos problem with the zooming consistency and panning consistency constraints. The objective of isos is to provide seamless experience for end-users to interactively explore the data by navigating the map. We extend our algorithm for the sos problem to solve the isos problem, and propose a new strategy based on pre-fetching to significantly enhance the efficiency. Finally we have conducted extensive experiments to show the efficiency and scalability of our approach.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://dl.acm.org/citation.cfm?id=3183738

---