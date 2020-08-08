---
title: "Finding Temporal Influential Users over Evolving Social Networks"
authors:
- Shixun Huang
- admin
- J.Shane Culpepper
- Bang Zhang

publication_types: ["1"]
publication: In *the 35th International Conference on Data Engineering (ICDE) 2019*
publication_short: In *IEEE ICDE 2019*
publishDate: "2019-04-11"

abstract: Influence maximization (IM) continues to be a key research problem in social networks. The goal is to find a small seed set of target users that have the greatest influence in the network under various stochastic diffusion models. While significant progress has been made on the IM problem in recent years, several interesting challenges remain. For example, social networks in reality are constantly evolving, and "important" users with the most influence also change over time. As a result, several recent studies have proposed approaches to update the seed set as the social networks evolve. However, this seed set is not guaranteed to be the best seed set over a period of time. In this paper we study the problem of Distinct Influence Maximization (DIM) where the goal is to identify a seed set of influencers who maximize the number of distinct users influenced over a predefined window of time. Our new approach allows social network providers to make fewer incremental changes to targeted advertising while still maximizing the coverage of the advertisements. It also provides finer grained control over service level agreements where a certain number of impressions for an advertisement must be displayed in a specific time period. We propose two different strategies HCS and VCS with novel graph compression techniques to solve this problem. Additionally, VCS can also be applied directly to the traditional IM problem. Extensive experiments on real-world datasets verify the efficiency, accuracy and scalability of our solutions on both the DIM and IM problems.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://ieeexplore.ieee.org/abstract/document/8731473
url_slides: 'slides/icde19-talk.pdf'

---