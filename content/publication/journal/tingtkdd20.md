---
title: "Efficient Mining of Outlying Sequence Patterns for Analyzing Outlierness of Sequence Data"
authors:
- Tingting Wang
- Lei Duan
- Guozhu Dong
- admin


publication_types: ["1"]
publication: In *ACM Transactions on Knowledge Discovery from Data*
publication_short: In *ACM TKDD*
publishDate: "2020-08-01"

abstract: Recently, a lot of research work has been proposed in different domains to detect outliers and analyze the outlierness of outliers for relational data. However, while sequence data is ubiquitous in real life, analyzing the outlierness for sequence data has not received enough attention. In this article, we study the problem of mining outlying sequence patterns in sequence data addressing the question: given a query sequence s in a sequence dataset D, the objective is to discover sequence patterns that will indicate the most unusualness (i.e., outlierness) of s compared against other sequences. Technically, we use the rank defined by the average probabilistic strength (aps) of a sequence pattern in a sequence to measure the outlierness of the sequence. Then a minimal sequence pattern where the query sequence is ranked the highest is defined as an outlying sequence pattern. To address the above problem, we present OSPMiner, a heuristic method that computes aps by incorporating several pruning techniques. Our empirical study using both real and synthetic data demonstrates that OSPMiner is effective and efficient.


#tags:
#- Source Themes
featured: true



links:
url_pdf: https://dl.acm.org/doi/fullHtml/10.1145/3399671

---