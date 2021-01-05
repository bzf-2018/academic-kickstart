---
title: "A Survey on Advancing the DBMS Query Optimizer: Cardinality
Estimation, Cost Model, and Plan Enumeration"
authors:
- Hai Lan
- admin
- Yuwei Peng

publication_types: ["1"]
publication: In *Data Science and Engineering (Invited Paper)*
publication_short: In *DSE*
publishDate: "2020-12-18"

abstract: 
Query optimizer is at the heart of the database systems. Cost-based optimizer studied in this paper is adopted in almost all current database systems. A cost-based optimizer introduces a plan enumeration algorithm to fi nd a (sub)plan, and then uses a cost model to obtain the cost of that plan, and selects the plan with the lowest cost. In the cost model, cardinality, the number of tuples through an operator, plays a crucial role. Due to the inaccuracy in cardinality estimation, errors in cost model, and the huge plan space, the optimizer cannot fi nd the optimal execution plan for a complex query in a reasonable time. In this paper, we first deeply study the causes behind the limitations above. Next, we review the techniques used to improve the quality of the three key components in the cost-based optimizer, cardinality estimation, cost model, and plan
enumeration. We also provide our insights on the future directions for each of the above aspects.

#tags:
#- Source Themes
featured: true



links:
url_pdf: 'papers/survey_optimizer20.pdf'

---