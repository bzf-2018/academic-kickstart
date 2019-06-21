---
title: "Answering Top-k Exemplar Trajectory Queries"
authors:
- Sheng Wang
- admin
- Timos Sellis
- Mark Sanderson
- Xiaolin Qin

publication_types: ["1"]
publication: In *the 33th International Conference on Data Engineering (ICDE)*
publication_short: In *ICDE*
publishDate: "2017-04-19"

abstract: We study a new type of spatial-textual trajectory
search - the Exemplar Trajectory Query (ETQ), which specifies
one or more places to visit, and descriptions of activities at
each place. Our goal is to efficiently find the top-k trajectories by computing spatial and textual similarity at each point. The computational cost for pointwise matching is significantly higher than previous approaches. Therefore, we introduce an incremental pruning baseline and explore how to adaptively tune our approach, introducing a gap-based optimization and a novel twolevel threshold algorithm to improve efficiency. Our proposed methods support order-sensitive ETQ with a minor extension. Experiments on two datasets verify the efficiency and scalability of our proposed solution.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://ieeexplore.ieee.org/abstract/document/7930010

---