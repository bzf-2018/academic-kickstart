---
title: "VRE: A Versatile, Robust, and Economical Trajectory Data System"
authors:
- Hai Lan
- Jiong Xie
- admin
- Feifei Li
- W Tian
- Fang Wang
- Sheng Wang
- Ailin Zhang

publication_types: ["1"]
publication: In *VLDB 2022*
publication_short: In *VLDB 2022*
publishDate: "2022-05-08"

abstract: Managing massive trajectory data from various moving objects has
always been a demanding task. A desired trajectory data system
should be versatile in its supported query types and distance functions,
of low storage cost, and be consistently efficient on processing
trajectory data of different properties. Unfortunately, none of the
existing systems can meet the above three criteria at the same time.
To this end, we propose VRE, a versatile, robust, and economical
trajectory data system.VRE separates the storage from the processing.
In the storage layer, we propose a novel segment-based storage
model that takes advantage of the strengths of both point-based and
trajectory-based storage models. VRE supports these three storage
models and ten storage schemas upon them. With the secondary
index, VRE reduces the storage cost up to 3x. In the processing
layer, we first propose a two-stage processing framework and a
pushdown strategy to alleviate full trajectory transmission cost.
Then, we design a unified pruning strategy for five widely used
trajectory distance functions and numerous tailored processing
algorithms for five advanced queries. Extensive experiments are
conducted to verify the design choice and efficiency of VRE. More
importantly, we present some key insights through our evaluation,
which are crucial to both VRE and future trajectory system’s design.

#tags:
#- Source Themes
featured: true

links:
---