---
title: "Torch: A Search Engine for Trajectory Data"
authors:
- Sheng Wang
- admin
- J. Shane Culpepper
- Zizhe Xie
- Qizhi Liu
- Xiaolin Qin

publication_types: ["1"]
publication: In *the 41st International Conference on Research and Development in Information Retrieval (SIGIR)*
publication_short: In *SIGIR*
publishDate: "2018-07-08"

abstract: This paper presents a new trajectory search engine called Torch for querying road network trajectory data. Torch is able to efficiently process two types of typical queries (similarity search and Boolean search), and support a wide variety of trajectory similarity functions. Additionally, we propose a new similarity function LORS in Torch to measure the similarity in a more effective and efficient manner. Indexing and search in Torch works as follows. First, each raw vehicle trajectory is transformed to a set of road segments (edges) and a set of crossings (vertices) on the road network. Then a lightweight edge and vertex index called LEVI is built. Given a query, a filtering framework over LEVI is used to dynamically prune the trajectory search space based on the similarity measure imposed. Finally, the result set (ranked or Boolean) is returned. Extensive experiments on real trajectory datasets verify the effectiveness and efficiency of Torch.


#tags:
#- Source Themes
featured: true

links:
- name: System
  url: https://www.google.com/url?q=https%3A%2F%2Ft4research.github.io%2F&sa=D&sntz=1&usg=AFQjCNF7ZYH7ImilgfdVhY8E0OTk5p-_eQ
- name: Code
  url: https://github.com/tgbnhy/torch-trajectory
url_pdf: http://culpepper.io/publications/wbc+18-sigir.pdf
url_slides: https://drive.google.com/file/d/1oYIPCib4f9Ggz2cXM8YiH3uuebWySOrH/view
url_video: https://www.youtube.com/watch?v=CF1tlrRTV18&feature=youtu.be

---