---
title: "Reverse k Nearest Neighbor Search over Trajectories"
authors:
- Sheng Wang
- admin
- J. Shane Culpepper
- Timos Sellis
- Gao Cong

publication_types: ["1"]
publication: In *the 33th International Conference on Data Engineering (ICDE)*
publication_short: In *ICDE*
publishDate: "2017-04-19"

abstract: GPS enables mobile devices to continuously provide new opportunities to improve our daily lives. For example, the data collected in applications created by Uber or Public Transport Authorities can be used to plan transportation routes, estimate capacities, and proactively identify low coverage areas. In this paper, we study a new kind of query-Reverse k Nearest Neighbor Search over Trajectories (RkNNT), which can be used for route planning and capacity estimation. Given a set of existing routes D_R , a set of passenger transitions D_T , and a query route Q, an RkNNT query returns all transitions that take Q as one of its k nearest travel routes. To solve the problem, we first develop an index to handle dynamic trajectory updates, so that the most up-to-date transition data are available for answering an RkNNT query. Then we introduce a filter refinement framework for processing RkNNT queries using the proposed indexes. Next, we show how to use RkNNT to solve the optimal route planning problem MaxRkNNT (MinRkNNT), which is to search for the optimal route from a start location to an end location that could attract the maximum (or minimum) number of passengers based on a predefined travel distance threshold. Experiments on real datasets demonstrate the efficiency and scalability of our approaches. To the best of our knowledge, this is the first work to study the RkNNT problem for route planning.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://ieeexplore.ieee.org/abstract/document/8118111

---