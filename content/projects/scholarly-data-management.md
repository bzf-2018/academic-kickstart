---
title: Scholarly Data Management
linktitle: Scholarly Data Management
toc: true
type: docs
draft: false
lastmod: "2026-07-11T00:00:00Z"
weight: 25

menu:
  projects:
    name: Scholarly Data Management
    weight: 25
---

---

## Topic 1: Conference Program Management

**1.1) TaxoConf: A Taxonomy-Driven System for Conference Program Management ([System Prototype](https://taxoconf.com))**

TaxoConf is a system that automates the construction of coherent technical programs for large academic conferences. Given a set of accepted papers, it induces a topic taxonomy from paper abstracts and uses it to organize papers into thematically coherent oral and poster sessions, while jointly minimizing author scheduling conflicts and respecting capacity constraints on session sizes, parallel rooms, and time slots.

The system offers four key features: (1) accurate and coherent grouping of papers into sessions through taxonomy-guided topical clustering; (2) a unified, high-level schedule that consistently organizes sessions across multiple tracks; (3) flexible and convenient human-in-the-loop modification, allowing organizers to refine automatically generated programs with ease; and (4) diverse and practical data exports, enabling users to produce CSV or Excel files that can be readily imported into conference apps, as well as a rich, detailed HTML program page for attendee navigation.

TaxoConf has been adopted to help organize the programs of top computer science conferences, including [SIGIR 2026](https://sigir2026.org/en-AU) and [IJCNN 2026](https://sites.google.com/view/ijcnn2026-emergent-gpais), and is deployed as a live web application at [taxoconf.com](https://taxoconf.com/).

{{< figure_video src="projects/scholarly-data-management/taxoconf.png" library="1" >}}

---

**1.2) Who Should Review—and Who Is Missing? Toward Accurate Reviewer Assignment and Scalable Expert Discovery**

Accurate paper–reviewer assignment is essential to the quality and integrity of scientific peer review, yet existing systems face two fundamental pain points. 1) **Inaccurate assignment due to coarse expertise modeling**. Most existing methods represent each submission and reviewer using a flat, single-vector embedding. By compressing multi-faceted research topics into coarse semantic centroids, these representations cannot reliably distinguish fine-grained technical expertise from broad or superficial topical overlap. Consequently, partially relevant reviewers may receive high affinity scores, while genuinely suitable experts may be overlooked. 2) **Inability to discover experts beyond a fixed reviewer panel**. Existing conference-management platforms typically assume that the reviewer panel is fixed. When the available panel lacks sufficient expertise in emerging, interdisciplinary, or highly specialized topics, program chairs must manually recruit additional reviewers through personal networks, ad hoc searches, or inspection of related publications. This process is time-consuming, difficult to scale, and potentially biased toward familiar research communities.

This project develops **ReviewAtlas**, a scholarly data management system that jointly supports accurate reviewer assignment and scalable expert discovery. For reviewer assignment, ReviewAtlas constructs a conference-specific weighted taxonomy and represents submissions and reviewers as distributions over fine-grained topics. It measures their alignment using tree–Wasserstein distance, thereby preserving multi-faceted expertise and distinguishing genuine technical depth from high-level topical similarity. For expert discovery, ReviewAtlas organizes a large, continuously updated expert lake using a persistent global expertise taxonomy. A global–local alignment mechanism calibrates external expert retrieval against the conference-specific expertise structure, enabling the system to identify qualified and promising experts who can address uncovered submission topics. Together, these capabilities provide a unified and scalable foundation for improving both reviewer-assignment fidelity and reviewer-panel coverage.

{{< figure_video src="projects/scholarly-data-management/reviewatlas.pdf" library="1" >}}

---

## Topic 2: Taxonomy Maintenance In The Wild Over Evolving Scholarly Data

**Taxonomy Maintenance In The Wild Over Evolving Scholarly Data: Reliability, Efficiency, and Cost-Effectiveness [SIGMOD 2027]**

{{< modality_badges "text" >}}

Taxonomy is a structured “topic map” that organizes concepts into a hierarchy (e.g., Machine Learning → Deep Learning → Graph Neural Networks), helping people and systems navigate, search, and reason about a domain. However, modern research fields evolve so quickly that any hand-crafted taxonomy can become outdated within months. This paper studies taxonomy maintenance in the wild: continuously updating a topic taxonomy as new papers stream into open repositories such as arXiv, where terminology shifts, subareas split into finer themes, and higher-level categories must be reorganized over time. To address this challenge, the paper proposes GIST, a taxonomy maintenance framework with three desirable properties: 1) Robust. Instead of asking an LLM to directly “invent” taxonomy structure, GIST grounds updates in author-written evidence by extracting small, reliable topic hierarchies from papers’ Related Work sections. 2) Scalable. GIST supports continual updates through incremental learning, using a novelty-aware coreset (a compact, representative memory of past evidence) to avoid expensive full retraining over all historical papers. 3) Cost-effective. GIST operates under a user-specified token budget: a budget-aware planner decides what to retrieve and which papers to parse so that only the most informative evidence is processed at each update.

{{< figure_video src="projects/data-orchestration-for-ai/gist.png" width="600" library="1" >}}

