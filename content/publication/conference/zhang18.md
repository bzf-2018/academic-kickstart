---
title: "Trajectory-driven Influential Billboard Placement"
authors:
- Ping Zhang
- admin
- Yuchen Li
- Guoliang Li
- Zhiyong Peng

publication_types: ["1"]
publication: In *the 24th International Conference on Knowledge Discovery and Data Mining (KDD)*
publication_short: In *KDD*
publishDate: "2018-08-13"

abstract: In this paper we propose and study the problem of trajectory driven influential billboard placement. Given a set of billboards U (each with a location and a cost), a database of trajectories T and a budget L, find a set of billboards within the budget to influence the largest number of trajectories. One core challenge is to identify and reduce the overlap of the influence from different billboards to the same trajectories, while keeping the budget constraint into consideration. We show that this problem is NP-hard and present an enumeration based algorithm with (1 − 1/e) approximation ratio. However, the enumeration should be very costly when |U| is large. By exploiting the locality property of billboards’ influence, we propose a partition-based framework PartSel. PartSel partitions U into a set of small clusters, computes the locally influential billboards for each cluster, and merges them to generate the global solution. Since the local solutions can be obtained much more efficient than the global one, PartSel should reduce the computation cost greatly; meanwhile it achieves a non-trivial approximation ratio guarantee. Then we propose a LazyProbe method to further prune billboards with low marginal influence, while achieving the same approximation ratio as PartSel. Experiments on real datasets verify the efficiency and effectiveness of our methods.

summary: Given a set of billboards U (each with a location and a cost), a database of trajectories T and a budget L, find a set of billboards within the budget to influence the largest number of trajectories.

#tags:
#- Source Themes
featured: true

links:
url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_video: '#'

---