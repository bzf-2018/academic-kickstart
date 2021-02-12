---
title: "Temporal Network Representation Learning via Historical Neighborhoods Aggregation"
authors:
- Shixun Huang
- Yuchen Li
- admin
- Zhao Li


publication_types: ["1"]
publication: In *the 37th International Conference on Data Engineering (ICDE) 2021*
publication_short: In *IEEE ICDE 2021*
date: "2020-10-10"

abstract: In this paper, we study the problem of efﬁcient motif-based graph partitioning (MGP). We observe that existing methods require to enumerate all motif instances to compute the exact edge weights for partitioning. However, the enumeration is prohibitively expensive against large graphs. We thus propose a sampling-based MGP (SMGP) framework that employs an unbiased sampling mechanism to efﬁciently estimate the edge weights while trying to preserve the partitioning quality. To
further improve the effectiveness, we propose a novel adaptive sampling framework called SMGP+. SMGP+ iteratively partitions the input graph based on up-to-date estimated edge weights, and adaptively adjusts the sampling distribution so that the edges that are more likely to affect the partitioning outcome will be prioritized for weight estimation. To our best knowledge, this is the ﬁrst attempt to solve the MGP problem without employing exact edge weight computations, which gives hope for existing MGP methods to perform on complicated motifs in a scalable yet effective manner. Extensive experiments on seven real-world datasets have validated that our framework delivers competitive partitioning quality compared to existing workﬂows based on exact edge weights, while achieving orders of magnitude speedup.


#tags:
#- Source Themes
featured: true

links:
url_pdf: ICDE21-gp-TR.pdf


---