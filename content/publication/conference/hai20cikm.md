---
title: "An Index Advisor Using Deep Reinforcement Learning"
authors:
- Hai Lan
- admin
- Yuwei Peng

publication_types: ["1"]
publication: In *29th ACM International Conference on Information and Knowledge Management*
publication_short: In *ACM CIKM*
publishDate: "2020-10-19"

abstract: We study the problem of index selection to maximize the workload performance, which is critical to database systems. In contrast to existing methods, we seamlessly integrate index recommendation rules and deep reinforcement learning, such that we can recommend single-attribute and multi-attribute indexes together for complex queries and meanwhile support multiple-index access to a table. Specifically, we first propose five heuristic rules to generate the index candidates. Then, we formulate the index selection problem as a reinforcement learning task and employ Deep Q Network (DQN) on it. Using the heuristic rules can significantly reduce the dimensions of the action space and state space in reinforcement learning. With the neural network used in DQN, we can model the interactions between indexes better than previous methods. We conduct experiments on various workloads to show its superiority.

#tags:
#- Source Themes
featured: true


links:
- name: Code
  url: https://github.com/rmitbggroup/IndexAdvisor
  
url_pdf: 'papers/cikm20-IndexRec.pdf'
url_slides: 'slides/CIKM20_Index_slides.pdf'

---