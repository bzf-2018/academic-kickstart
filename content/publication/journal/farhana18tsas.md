---
title: "Batch Processing of Top-k Spatial-Textual Queries"
authors:
- Farhana M. Choudhury
- J. Shane Culpepper
- admin
- Timos Sellis

publication_types: ["2"]
publication: In *Transactions on Spatial Algorithms and Systems (TSAS)*
publication_short: In *TSAS (2018)*
publishDate: "2018-05-19"

abstract: Since the mid-2000s, everal indexing techniques have been proposed to efficiently answer top-k spatial-textual queries. However, all of these approaches focus on answering one query at a time. In contrast, how to design efficient algorithms that can exploit similarities between incoming queries to improve performance has received little attention. In this article, we study a series of efficient approaches to batch process multiple top-k spatial-textual queries concurrently. We carefully design a variety of indexing structures for the problem space by exploring the effect of prioritizing spatial and textual properties on system performance. Specifically, we present an efficient traversal method, SF-Sep, over an existing space-prioritized index structure. Then, we propose a new space-prioritized index structure, the MIR-Tree to support a filter-and-refine based technique, SF-Grp. To support the processing of text-intensive data, we propose an augmented, inverted indexing structure that can easily be added into existing text search engine architectures and a novel traversal method for batch processing of the queries. In all of these approaches, the goal is to improve the overall performance by sharing the I/O costs of similar queries. Finally, we demonstrate significant I/O savings in our algorithms over traditional approaches by extensive experiments on three real datasets and compare how properties of different datasets affect the performance. Many applications in streaming, micro-batching of continuous queries, and privacy-aware search can benefit from this line of work.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://dl.acm.org/citation.cfm?id=3196155

---