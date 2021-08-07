---
title: "How Context or Knowledge Can Benefit Healthcare Question Answering?"
authors:
- Xiaoli Wang
- Feng Luo
- Qingfeng Wu
- admin

publication_types: ["1"]
publication: In *the Transactions on Knowledge and Data Engineering (TKDE)*
publication_short: In *TKDE*
publishDate: "2021-06-19"

abstract: Healthcare question answering (HQA) is a challenging task as questions are generally non-factoid. Recent neural systems are reported to have performance gains. However, little attention has been given to HQA as datasets are generally too small to train a neural model from scratch. Recently, several systems have been proposed to learn context representations for HQA. Despite moderate progress, these systems have not been thoroughly compared with state-of-the-art neural models, and the mentioned models are tested only on self-created datasets. To address the challenges, we develop a new joint model to incorporate both context and knowledge embeddings into neural ranking architectures. First, we adapt context embedding pre-trained from large open-domain corpus to small healthcare datasets. Second, we learn knowledge embedding from knowledge graphs to provide external information for understanding non-factoid questions. To evaluate our framework, we adapt many state-of-the-art methods for general QA to HQA, by injecting the context or knowledge information only, or both of them. Extensive experiments are conducted to compare our approach with those adapted methods and current HQA systems. The results show that our approach achieves the state-of-the-art performance on both HealthQA and NFCorpus datasets.


#tags:
#- Source Themes
featured: true


links:
- name: Code
  url: https://github.com/emmali808/HQADeepHelper
url_pdf: 'papers/tkde21-hqa.pdf'

---