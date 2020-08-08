---
title: "Spatial Object Recommendation with Hints - When Spatial Granularity Matters"
authors:
- Hui Luo
- Jingbo Zhou
- admin
- Shangli Li
- J.Shane Culpepper
- Haochao Ying
- Hao Liu
- Hui Xiong

publication_types: ["1"]
publication: In *the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR)*
publication_short: In *SIGIR*
publishDate: "2020-07-20"

abstract: Existing spatial object recommendation algorithms generally treat objects identically when ranking them. However, spatial objects often cover different levels of spatial granularity and thereby are heterogeneous. For example, one user may prefer to be recom- mended a region (say Manhattan), while another user might prefer a venue (say a restaurant). Even for the same user, preferences can change at different stages of data exploration. In this paper, we study how to support top-𝑘 spatial object recommendations at varying levels of spatial granularity, enabling spatial objects at have granularity, such as a city, suburb, or building, as a Point of Interest (POI). To solve this problem, we propose the use of a POI tree, which captures spatial containment relationships between POIs. We design a novel multi-task learning model called MPR (short for Multi-level POI Recommendation), where each task aims to re- turn the top-𝑘 POIs at a certain spatial granularity level. Each task consists of two subtasks - (i) attribute-based representation learning; (ii) interaction-based representation learning. The first subtask learns the feature representations for both users and POIs, capturing attributes directly from their profiles. The second subtask incorpo- rates user-POI interactions into the model. Additionally, MPR can provide insights into why certain recommendations are being made to a user based on three types of hints - user-aspect, POI-aspect, and interaction-aspect. We empirically validate our approach using two real-life datasets, and show promising performance improvements over several state-of-the-art methods.


#tags:
#- Source Themes
featured: true

links:
- name: Video
url: https://youtu.be/3Da0EqYVOqk
url_pdf: 'papers/hui20sigir.pdf'

---