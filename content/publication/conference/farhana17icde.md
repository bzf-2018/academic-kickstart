---
title: "Monitoring the Top-m Rank Aggregation of Spatial Objects in Streaming Queries"
authors:
- Farhana M. Choudhury
- admin
- J. Shane Culpepper
- Timos Sellis

publication_types: ["1"]
publication: In *the 33th International Conference on Data Engineering (ICDE)*
publication_short: In *ICDE*
publishDate: "2017-04-19"

abstract: In this paper, we propose and study the problem of top-m rank aggregation of spatial objects in streaming queries, where, given a set of objects O, a stream of spatial queries (kNN or range), the goal is to report the m objects with the highest aggregate rank. The rank of an object with respect to an individual query is computed based on its distance from the query location, and the aggregate rank is computed from all of the individual rank orderings. In order to solve this problem, we show how to upper and lower bound the rank of an object for any unseen query. Then we propose an approximation solution to continuously monitor the top-m objects efficiently, for which we design an Inverted Rank File (IRF) index to guarantee the error bound of the solution. In particular, we propose the notion of safe ranking to determine whether the current result is still valid or not when new queries arrive, and propose the notion of validation objects to limit the number of objects to update in the top-m results. We also propose an exact solution for applications where an approximate solution is not sufficient. Last, we conduct extensive experiments to verify the efficiency and effectiveness of our solutions. This is a fundamental problem that draws inspiration from three different domains - rank aggregation, continuous queries and spatial databases, and the solution can be used to monitor the importance / popularity of spatial objects, which in turn can provide new analytical tools for spatial data.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://ieeexplore.ieee.org/abstract/document/7930009

---