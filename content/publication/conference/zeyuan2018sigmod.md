---
title: "POIsam: a System for Efficient Selection of Large-scale Geospatial Data on Maps"
authors:
- Zeyuan Shang
- Guoliang Li
- admin

publication_types: ["1"]
publication: In *the 2018 International Conference on Management of Data (SIGMOD)*
publication_short: In *SIGMOD*
publishDate: "2018-06-10"

abstract: Trajectory analytics can benefit many real-world applications, e.g., frequent trajectory based navigation systems, road planning, car pooling, and transportation optimizations. Existing algorithms focus on optimizing this problem in a single machine. However, the amount of trajectories exceeds the storage and processing capability of a single machine, and it calls for large-scale trajectory analytics in distributed environments. The distributed trajectory analytics faces challenges of data locality aware partitioning, load balance, easy-to-use interface, and versatility to support various trajectory similarity functions. To address these challenges, we propose a distributed in-memory trajectory analytics system DITA. We propose an effective partitioning method, global index and local index, to address the data locality problem. We devise cost-based techniques to balance the workload. We develop a filter-verification framework to improve the performance. Moreover, DITA can support most of existing similarity functions to quantify the similarity between trajectories. We integrate our framework seamlessly into Spark SQL, and make it support SQL and DataFrame API interfaces. We have conducted extensive experiments on real world datasets, and experimental results show that DITA outperforms existing distributed trajectory similarity search and join approaches significantly.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://dl.acm.org/citation.cfm?id=3183743

---