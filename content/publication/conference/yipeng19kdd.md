---
title: "Optimizing Impression Counts for Outdoor Advertising"
authors:
- Yipeng Zhang
- Yuchen Li
- admin
- Songsong Mo
- Ping Zhang

publication_types: ["1"]
publication: In *the 25th International Conference on Knowledge Discovery and Data Mining (KDD)*
publication_short: In *KDD*
publishDate: "2019-08-04"

abstract: In this paper we propose and study the problem of optimizing the influence of outdoor advertising (ad) when impression counts are taken into consideration. Given a database U of billboards, each of which has a location and a non-uniform cost, a trajectory database T and a budget B, it aims to find a set of billboards that has the maximum influence under the budget. In line with the advertising consumer behavior studies, we adopt the logistic function to take into account the impression counts of an ad (placed at different billboards) to a user trajectory when defining the influence measurement. However, this poses two challenges - (1) our problem is NP-hard to approximate within a factor of O(|T|1-ε) for any ε>0 in polynomial time; (2) the influence measurement is non-submodular, which means a straightforward greedy approach is not applicable. Therefore, we propose a tangent line based algorithm to compute a submodular function to estimate the upper bound of influence. Henceforth, we introduce a branch-and-bound framework with a θ-termination condition, achieving θ2/(1 - 1/e) approximation ratio. However, this framework is time-consuming when |U| is huge. Thus, we further optimize it with a progressive pruning upper bound estimation approach which achieves θ2/(1 - 1/e - ε) approximation ratio and significantly decreases the running-time. We conduct the experiments on real-world billboard and trajectory datasets, and show that the proposed approaches outperform the baselines by 95% in effectiveness. Moreover, the optimized approach is around two orders of magnitude faster than the original framework.


#tags:
#- Source Themes
featured: true

links:
url_pdf: 'slides/yipeng19kddpaper.pdf'
url_slides: 'slides/yipeng19kdd.pptx'

---