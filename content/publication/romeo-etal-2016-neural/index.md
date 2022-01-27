---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Neural Attention for Learning to Rank Questions in Community Question Answering
subtitle: ''
summary: ''
authors:
- Salvatore Romeo
- Giovanni Da San Martino
- Alberto Barrón-Cedeño
- Alessandro Moschitti
- Yonatan Belinkov
- Wei-Ning Hsu
- Yu Zhang
- Mitra Mohtarami
- James Glass
tags: []
categories: []
date: '2016-12-01'
lastmod: 2022-01-27T17:35:07+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-01-27T18:00:18.158429Z'
publication_types:
- '1'
abstract: In real-world data, e.g., from Web forums, text is often contaminated with
  redundant or irrelevant content, which leads to introducing noise in machine learning
  algorithms. In this paper, we apply Long Short-Term Memory networks with an attention
  mechanism, which can select important parts of text for the task of similar question
  retrieval from community Question Answering (cQA) forums. In particular, we use
  the attention weights for both selecting entire sentences and their subparts, i.e.,
  word/chunk, from shallow syntactic trees. More interestingly, we apply tree kernels
  to the filtered text representations, thus exploiting the implicit features of the
  subtree space for learning question reranking. Our results show that the attention-based
  pruning allows for achieving the top position in the cQA challenge of SemEval 2016,
  with a relatively large gap from the other participants while greatly decreasing
  running time.
publication: '*Proceedings of COLING 2016, the 26th International Conference on Computational
  Linguistics: Technical Papers*'
links:
- name: URL
  url: https://aclanthology.org/C16-1163
---
