---
title: "Towards an Optimal Outdoor Advertising Placement - When a Budget Constraint Meets Moving Trajectories"
authors:
- Ping Zhang
- admin
- Yuchen Li
- Guoliang Li
- Yipeng Zhang
- Zhiyong Peng

publication_types: ["1"]
publication: In *ACM Transactions on Knowledge Discovery from Data*
publication_short: In *ACM TKDD*
date: "2020-07-17"

abstract: In this article, we propose and study the problem of trajectory-driven influential billboard placement: given a set of billboards U (each with a location and a cost), a database of trajectories T, and a budget L, we find a set of billboards within the budget to influence the largest number of trajectories. One core challenge is to identify and reduce the overlap of the influence from different billboards to the same trajectories, while keeping the budget constraint into consideration. We show that this problem is NP-hard and present an enumeration based algorithm with (1-1/e) approximation ratio. However, the enumeration would be very costly when |U| is large. By exploiting the locality property of billboards' influence, we propose a partition-based framework PartSel. PartSel partitions U into a set of small clusters, computes the locally influential billboards for each cluster, and merges them to generate the global solution. Since the local solutions can be obtained much more efficiently than the global one, PartSel would reduce the computation cost greatly; meanwhile it achieves a non-trivial approximation ratio guarantee. Then we propose a LazyProbe method to further prune billboards with low marginal influence, while achieving the same approximation ratio as PartSel. Next, we propose a branch-and-bound method to eliminate unnecessary enumerations in both PartSel and LazyProbe, as well as an aggregated index to speed up the computation of marginal influence. Experiments on real datasets verify the efficiency and effectiveness of our methods.


#tags:
#- Source Themes
featured: true



links:
url_pdf: 'papers/tkdd20-a.pdf'

---