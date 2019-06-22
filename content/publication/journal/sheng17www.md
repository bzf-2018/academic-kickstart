---
title: "Tide-tree: A self-tuning indexing scheme for hybrid storage system"
authors:
- Sheng Wang
- Xiaolin Qin
- admin
- Bohan Li

publication_types: ["1"]
publication: In *the World Wide Web Journal*
publication_short: In *WWWJ (2017)*
publishDate: "2017-09-19"

abstract: Main memory index is built with the assumption that the RAM is sufficiently large to hold data. Due to the volatility and high unit price of main memory, indices under secondary memory such as SSD and HDD are widely used. However, the I/O operation with main memory is still the bottleneck for query efficiency. In this paper, we propose a self-tuning indexing scheme called Tide-tree for RAM/Disk-based hybrid storage system. Tide-tree aims to overcome the obstacles main memory and disk-based indices face, and performs like the tide to achieve a double-win in space and performance, which is self-adaptive with respect to the running environment. Particularly, Tide-tree delaminates the tree structure adaptively with high efficiency based on storage sense, and applies an effective self-tuning algorithm to dynamically load various nodes into main memory. We employ memory mapping technology to solve the persistent problem of main memory index, and improves the efficiency of data synchronism and pointer translation. To further enhance the independence of Tide-tree, we employ the index head and the level address table to manage the whole index. With the index head, three efficient operations are proposed, namely index rebuild, index load and range search. We have conducted extensive experiments to compare the Tide-tree with several state-of-the-art indices, and the results have validated the high efficiency, reusability and stability of Tide-tree.


#tags:
#- Source Themes
featured: true

links:
url_pdf: https://link.springer.com/article/10.1007/s11280-016-0426-9

---