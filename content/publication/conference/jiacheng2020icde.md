---
title: "Crowdsourced Collective Entity Resolution with Relational Match Propagation"
authors:
- Jiacheng Huang
- Wei Hu
- admin
- Yuzhong Qu

publication_types: ["1"]
publication: In *the 36th International Conference on Data Engineering (ICDE)*
publication_short: In *ICDE*
date: "2020-04-01"
publishDate: "2019-10-01"

abstract: Knowledge bases (KBs) store rich yet heterogeneous entities and facts. Entity resolution (ER) aims to identify entities in KBs which refer to the same real-world object. Recent studies have shown significant benefits of involving humans in the loop of ER. They often resolve entities with pairwise similarity measures over attribute values and resort to the crowds to label uncertain ones. However, existing methods still suffer from high labor costs and insufficient labeling to some extent. In this paper, we propose a novel approach called crowdsourced collective ER, which leverages the relationships between entities to infer matches jointly rather than independently. Specifically, it iteratively asks human workers to label picked entity pairs and propagates the labeling information to their neighbors in distance. During this process, we address the problems of candidate entity pruning, probabilistic propagation, optimal question selection and error- tolerant truth inference. Our experiments on real-world datasets demonstrate that, compared with state-of-the-art methods, our approach achieves superior accuracy with much less labeling.



#tags:
#- Source Themes
featured: true

links:
url_pdf: 'slides/ICDE20_CER.pdf'


---