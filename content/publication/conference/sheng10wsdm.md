---
title: "A Unified Processing Paradigm for Interactive Location-based Web Search"
authors:
- Sheng Wang
- admin
- Shixun Huang
- Rui Zhang

publication_types: ["1"]
publication: In *the 11th ACM International Conference on Web Search and Data Mining (WSDM)*
publication_short: In *WSDM*
publishDate: "2018-02-05"

abstract: This paper studies the location-based web search and aims to build a unified processing paradigm for two purposes - (1) efficiently support each of the various types of location-based queries (kNN query,top-k spatial-textual query, etc.) on two major forms of geo-tagged data, i.e., spatial point data such as geo-tagged web documents, and spatial trajectory data such as a sequence of geo-tagged travel blogs by a user; (2) support interactive search to provide quick response for a query session, within which a user usually keeps refining her query by either issuing different query types or specifying different constraints (e.g., adding a keyword and/or location, changing the choice of k, etc.) until she finds the desired results. To achieve this goal, we first propose a general Top-k query called Monotone Aggregate Spatial Keyword query-MASK, which is able to cover most types of location-based web search. Next, we develop a unified indexing (called Textual-Grid-Point Inverted Index) and query processing paradigm (called ETAIL Algorithm) to answer a single MASK query efficiently. Furthermore, we extend ETAIL to provide interactive search for multiple queries within one query session, by exploiting the commonality of textual and/or spatial dimension among queries. Last, extensive experiments on four real datasets verify the robustness and efficiency of our approach.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://dl.acm.org/citation.cfm?id=3159667


---