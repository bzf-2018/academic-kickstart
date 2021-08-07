---
title: "Incremental Preference Adjustment - a Graph Theoretical Approach"
authors:
- Liangjun Song
- Junhao Gan
- admin
- Boyu Ruan
- H. V. Jagadish
- Timos Sellis

publication_types: ["1"]
publication: In *the VLDB Journal*
publication_short: In *VLDB Journal*
date: "2020-08-05"

abstract: Learning users' preferences is critical to personalized search and recommendation. Most such systems depend on lists of items rank-ordered according to the user's preference. Ideally, we want the system to adjust its estimate of users' preferences after every interaction, thereby becoming progressively better at giving the user what she wants. We also want these adjustments to be gradual and explainable, so that the user is not surprised by wild swings in system rank ordering. In this paper, we support a rank-reversal operation on two items x and y for users - adjust the user's preference such that the personalized rank of x and y is reversed. We emphasize that this problem is orthogonal to the preference learning and its solutions can run on top of the learning outcome of any vector-embedding-based preference learning model. Therefore, our preference adjustment techniques enable all those existing offline preference learning models to incrementally and interactively improve their response to (indirectly specified) user preferences. Specifically, we define the Minimum Dimension Adjustment (MDA) problem, where the preference adjustments are under certain constraints imposed by a specific graph and the goal is to adjust a user's preference by reversing the personalized rank of two given items while minimizing the number of dimensions with value changed in the preference vector. We first prove that MDA is NP-hard, and then show that a 2.17-approximate solution can be obtained in polynomial time provided that an optimal solution to a carefully designed problem is given. Finally, we propose two efficient heuristic algorithms, where the first heuristic algorithm can achieve an approximation guarantee, and the second is provably efficient. Experiments on five publicly available datasets show that our solutions can adjust users' preferences effectively and efficiently.


#tags:
#- Source Themes
featured: true



links:
- name: Code
  url: https://github.com/rmitbggroup/rank-reversal
- name: short video
  url: https://youtu.be/qcAcoS_321Q
url_pdf: 'papers/vldbj20-p.pdf'

---