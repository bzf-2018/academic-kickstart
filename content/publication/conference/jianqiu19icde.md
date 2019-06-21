---
title: "Continuous Range Queries Over Multi-attribute Trajectories"
authors:
- Jianqiu Xu
- admin
- Hua Lu

publication_types: ["1"]
publication: In *the 35th International Conference on Data Engineering (ICDE)*
publication_short: In *ICDE*
publishDate: "2019-08-11"

abstract: A multi-attribute trajectory consists of a sequence of time-stamped locations and a set of attributes that characterize diverse aspects of the corresponding moving object. In this paper, we study continuous range queries over multi-attribute trajectories. Such a query returns the objects whose attributes contain expected values and whose locations are always within a distance threshold to the query trajectory during the entire overlapping time period. To efficiently answer the query, an optimal method of partitioning the trajectories is proposed and an index structure is developed to support the combined search of spatio-temporal parameters and attribute values. We provide a general solution that is able to process multi-attribute trajectories as well as traditional trajectories without attributes. We carry out comprehensive experiments in a prototype database system to evaluate the efficiency and scalability of our designs. The experimental results show that our approach outperforms five alternative approaches by a factor of 5-50x on large datasets.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://ieeexplore.ieee.org/abstract/document/8731413

---