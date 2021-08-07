---
title: "A Framework to Support Continuous Range Queries over Multi-Attribute Trajectories"
authors:
- Jianqiu Xu
- admin
- Hua Lu

publication_types: ["1"]
publication: In *the Transactions on Knowledge and Data Engineering (TKDE)*
publication_short: In *TKDE*
publishDate: "2021-07-31"

abstract: Emerging applications over spatio-temporal trajectories require representing the data from diverse aspects. We study multi-attribute trajectories each of which consists of a sequence of time-stamped locations and a set of attributes characterizing diverse aspects. We investigate continuous range queries over multi-attribute trajectories. Such a query returns trajectories whose attributes contain expected values and whose locations are always within a distance threshold to the query trajectory during the entire overlapping time period. To efficiently answer the query, an optimal method of partitioning the trajectories is proposed and an index structure is developed to support the combined search using both spatio-temporal parameters and attribute values. Query algorithms and auxiliary structures are developed, accompanied with optimization strategies and thorough theoretical analysis. Using both real and synthetic datasets, we carry out comprehensive experiments in a prototype database system to evaluate the efficiency and scalability of our designs. The experimental results show that our approach outperforms six alternative approaches by a factor of 5-50x on large datasets.


#tags:
#- Source Themes
featured: true


links:
url_pdf: 'papers/tkde21-mat.pdf'

---