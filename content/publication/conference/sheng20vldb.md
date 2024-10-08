---
title: "Fast Large-Scale Trajectory Clustering"
authors:
- Sheng Wang
- admin
- J.Shane Culpepper
- Timos Sellis
- Xiaolin Qin

publication_types: ["1"]
publication: In *46th International Conference on Very Large Data Bases (VLDB)*
publication_short: In *VLDB*
date: "2020-08-01"
publishDate: "2019-11-02"

abstract: In this paper, we study the problem of large-scale trajectory data clustering, k-paths, which aims to efficiently identify k representative paths in a road network. Unlike traditional clustering approaches that require multiple data-dependent hyperparameters, k-paths can be used for visual exploration in applications such as traffic monitoring, public transit planning, and site selection. By combining map matching with an efficient intermediate representation of trajectories and a novel edge-based distance (EBD) measure, we present a scalable clustering method to solve k-paths. Experiments verify that we can cluster millions of taxi trajectories in less than one minute, achieving improvements of up to two orders of magnitude over state-of-the-art solutions that solve similar trajectory clustering problems.


#tags:
#- Source Themes
featured: true

links:
- name: Code
  url: https://github.com/tgbnhy/k-paths-clustering
url_pdf: http://www.vldb.org/pvldb/vol13/p29-wang.pdf

---