---
title: Scholarly Data Management
linktitle: Scholarly Data Management
toc: true
type: docs
draft: false
lastmod: "2026-05-18T00:00:00Z"
weight: 25

menu:
  projects:
    name: Scholarly Data Management
    weight: 25
---

---

## Topic 1: Conference Program Management

**TaxoConf: A Taxonomy-Driven System for Conference Program Management ([System Prototype](https://taxoconf.com))**

TaxoConf is a system that automates the construction of coherent technical programs for large academic conferences. Given a set of accepted papers, it induces a topic taxonomy from paper abstracts and uses it to organize papers into thematically coherent oral and poster sessions, while jointly minimizing author scheduling conflicts and respecting capacity constraints on session sizes, parallel rooms, and time slots.

The system offers four key features: (1) accurate and coherent grouping of papers into sessions through taxonomy-guided topical clustering; (2) a unified, high-level schedule that consistently organizes sessions across multiple tracks; (3) flexible and convenient human-in-the-loop modification, allowing organizers to refine automatically generated programs with ease; and (4) diverse and practical data exports, enabling users to produce CSV or Excel files that can be readily imported into conference apps, as well as a rich, detailed HTML program page for attendee navigation.

TaxoConf has been adopted to help organize the programs of top computer science conferences, including [SIGIR 2026](https://sigir2026.org/en-AU) and [IJCNN 2026](https://sites.google.com/view/ijcnn2026-emergent-gpais), and is deployed as a live web application at [taxoconf.com](https://taxoconf.com/).

{{< figure_video src="projects/scholarly-data-management/taxoconf.png" library="1" >}}

---

## Topic 2: Taxonomy Maintenance In The Wild Over Evolving Scholarly Data

**Taxonomy Maintenance In The Wild Over Evolving Scholarly Data: Reliability, Efficiency, and Cost-Effectiveness [SIGMOD 2027]**

{{< modality_badges "text" >}}

Taxonomy is a structured “topic map” that organizes concepts into a hierarchy (e.g., Machine Learning → Deep Learning → Graph Neural Networks), helping people and systems navigate, search, and reason about a domain. However, modern research fields evolve so quickly that any hand-crafted taxonomy can become outdated within months. This paper studies taxonomy maintenance in the wild: continuously updating a topic taxonomy as new papers stream into open repositories such as arXiv, where terminology shifts, subareas split into finer themes, and higher-level categories must be reorganized over time. To address this challenge, the paper proposes GIST, a taxonomy maintenance framework with three desirable properties: 1) Robust. Instead of asking an LLM to directly “invent” taxonomy structure, GIST grounds updates in author-written evidence by extracting small, reliable topic hierarchies from papers’ Related Work sections. 2) Scalable. GIST supports continual updates through incremental learning, using a novelty-aware coreset (a compact, representative memory of past evidence) to avoid expensive full retraining over all historical papers. 3) Cost-effective. GIST operates under a user-specified token budget: a budget-aware planner decides what to retrieve and which papers to parse so that only the most informative evidence is processed at each update.

{{< figure_video src="projects/data-orchestration-for-ai/gist.png" width="600" library="1" >}}

