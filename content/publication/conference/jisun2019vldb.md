---
title: "Balance-aware distributed string similarity-based query processing system"
authors:
- Ji Sun
- Zeyuan Shang
- Guoliang Li
- Dong Deng
- admin

publication_types: ["1"]
publication: In *the 45rd International Conference on Very Large Data Bases (VLDB)*
publication_short: In *VLDB*
publishDate: "2019-07-10"

abstract: Data analysts spend more than 80% of time on data cleaning and integration in the whole process of data analytics due to data errors and inconsistencies. Similarity-based query processing is an important way to tolerate the errors and inconsistencies. However, similarity-based query processing is rather costly and traditional database cannot afford such expensive requirement. In this paper, we develop a distributed in-memory similarity-based query processing system called Dima. Dima supports four core similarity operations, i.e., similarity selection, similarity join, top-k selection and top-k join. Dima extends SQL for users to easily invoke these similarity-based operations in their data analysis tasks. To avoid expensive data transmission in a distributed environment, we propose balance-aware signatures where two records are similar if they share common signatures, and we can adaptively select the signatures to balance the workload. Dima builds signature-based global indexes and local indexes to support similarity operations. Since Spark is one of the widely adopted distributed in-memory computing systems, we have seamlessly integrated Dima into Spark and developed effective query optimization techniques in Spark. To the best of our knowledge, this is the first full-fledged distributed in-memory system that can support complex similarity-based query processing on large-scale datasets. We have conducted extensive experiments on four real-world datasets. Experimental results show that Dima outperforms state-of-the-art studies by 1--3 orders of magnitude and has good scalability.


#tags:
#- Source Themes
featured: true

links:
url_pdf: http://www.vldb.org/pvldb/vol12/p961-sun.pdf

---