---
title: "Dima: A Distributed In-Memory Similarity-Based Query Processing System"
authors:
- Ji Sun
- Zeyuan Shang
- Guoliang Li
- Dong Deng
- admin

publication_types: ["1"]
publication: In *the 43rd International Conference on Very Large Data Bases (VLDB)*
publication_short: In *VLDB*
publishDate: "2017-08-28"

abstract: Data analysts in industries spend more than 80% of time on data cleaning and integration in the whole process of data analytics due to data errors and inconsistencies. It calls for effective query processing techniques to tolerate the errors and inconsistencies. In this paper, we develop a distributed in-memory similarity-based query processing system called Dima. Dima supports two core similarity-based query operations, i.e., similarity search and similarity join. Dima extends the SQL programming interface for users to easily invoke these two operations in their data analysis jobs. To avoid expensive data transformation in a distributed environment, we design selectable signatures where two records approximately match if they share common signatures. More importantly, we can adaptively select the signatures to balance the workload. Dima builds signature-based global indexes and local indexes to support efficient similarity search and join. Since Spark is one of the widely adopted distributed in-memory computing systems, we have seamlessly integrated Dima into Spark and developed effective query optimization techniques in Spark. To the best of our knowledge, this is the first full-fledged distributed in-memory system that can support similarity-based query processing. We demonstrate our system in several scenarios, including entity matching, web table integration and query recommendation.


#tags:
#- Source Themes
featured: true

links:
- name: Demo
  url: https://github.com/TsinghuaDatabaseGroup/dima
url_pdf: https://dl.acm.org/citation.cfm?id=3137810

---