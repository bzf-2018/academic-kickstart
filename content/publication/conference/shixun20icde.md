---
title: "Temporal Network Representation Learning via Historical Neighborhoods Aggregation"
authors:
- Shixun Huang
- admin
- Guoliang Li
- Yanghao Zhou
- J.Shane Culpepper

publication_types: ["1"]
publication: In *the 36th International Conference on Data Engineering (ICDE)*
publication_short: In *ICDE*
date: "2020-04-01"
publishDate: "2019-10-01"

abstract: Network embedding is an effective method to learn low-dimensional representations of nodes, which can be applied to various real-life applications such as visualization, node clas- sification, and link prediction. Although significant progress has been made on this problem in recent years, several important challenges remain, such as how to properly capture temporal information in evolving networks. In practice, most networks are continually evolving. Some networks only add new edges or nodes such as authorship networks, while others support removal of nodes or edges such as internet data routing. If patterns exist in the changes of the network structure, we can better understand the relationships between nodes and the evolution of the network, which can be further leveraged to learn node representations with more meaningful information. In this paper, we propose an Embedding via Historical Neighborhoods Aggregation (EHNA) method. More specifically, we first propose a temporal random walk which can identify relevant nodes in historical neighborhoods which have impact on edge formations. Then we present a deep learning model which uses custom atten- tion mechanisms to generate node embeddings to directly capture temporal information in the underlying feature representations. We conduct extensive experiments on real-world datasets, and the results demonstrate the effectiveness of our new approach in the network reconstruction and the link prediction tasks.


#tags:
#- Source Themes
featured: true

links:
- name: Code
  url: https://github.com/rmitbggroup/ICDE2020TemporalNetworkEmbedding
url_pdf: https://arxiv.org/abs/2003.13212


---