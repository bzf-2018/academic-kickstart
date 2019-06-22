---
title: "Finding the optimal location and keywords in obstructed and unobstructed space"
authors:
- Farhana M. Choudhury
- J. Shane Culpepper
- admin
- Timos Sellis

publication_types: ["2"]
publication: In *VLDB Journal 2018*
publication_short: In *VLDBJ (2018)*
publishDate: "2018-04-19"

abstract: The problem of optimal location selection based on reverse k nearest neighbor (RkNN) queries has been extensively studied in spatial databases. In this work, we present a related query, denoted as a Maximized Bichromatic Reverse Spatial Textual k Nearest Neighbor (MaxST) query, that finds an optimal location and a set of keywords for an object so that the object is a kNN object for as many users as possible. Such a query has many practical applications including advertisements, where the query is to find the location and the text contents to include in an advertisement so that it is relevant to the maximum number of users. The visibility of the advertisements also has an important role in the users’ interests. In this work, we address two instances of the spatial relevance when ranking items - (1) the Euclidean distance and (2) the visibility. We carefully design a series of index structures and approaches to answer the MaxST for both instances. Specifically, we present (1) the Grp- topk approach that requires the computation of the top-k objects for all of the users first and then applies various pruning techniques to find the optimal location and keywords; (2) the Indiv- U approach, where we use similarity estimations to avoid computing the top-k objects of the users that cannot be a final result; and (3) the Index- U approach where we propose a hierarchical index structure over the users to improve pruning. We show that the keyword selection component in MaxST queries is NP-hard and present both approximate and exact solutions for the problem.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://link.springer.com/content/pdf/10.1007/s00778-018-0504-y.pdf

---