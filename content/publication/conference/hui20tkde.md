---
title: "Dynamic Ridesharing in Peak Travel Periods"
authors:
- Hui Luo
- admin
- Farhana M. Choudhury
- J.Shane Culpepper

publication_types: ["1"]
publication: In *the Transactions on Knowledge and Data Engineering (TKDE)*
publication_short: In *TKDE*
date: "2020-04-01"
publishDate: "2019-10-01"

abstract: In this paper, we propose and study a variant of the dynamic ridesharing problem with a specific focus on peak hours: Given a set of drivers and a set of rider requests, we aim to match drivers to each rider request by achieving two objectives: maximizing the served rate and minimizing the total additional distance, subject to a series of spatio-temporal constraints. Our problem can be distinguished from existing ridesharing solutions in three aspects: (1) Previous work did not fully explore the impact of peak travel periods where the number of rider requests is much greater than the number of available drivers. (2) Existing ridesharing solutions usually rely on single objective optimization techniques, such as minimizing the total travel cost (either distance or time). (3) When evaluating the overall system performance, the runtime spent on updating drivers’ trip schedules as per newly coming rider requests should be incorporated, while it is unfortunately excluded by most existing solutions. In order to achieve our goal, we propose an underlying index structure on top of a partitioned road network, and compute the lower bounds of the shortest path distance between any two vertices. Using the proposed index together with a set of new pruning rules, we develop an efficient algorithm to dynamically include new riders directly into an existing trip schedule of a driver. In order to respond to new rider requests more effectively, we propose two algorithms that bilaterally match drivers with rider requests. Finally, we perform extensive experiments on a large-scale test collection to validate the effectiveness and efficiency of the proposed methods.


#tags:
#- Source Themes
featured: true


---