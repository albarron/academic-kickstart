---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Identifying Useful Human Correction Feedback from an On-Line Machine Translation
  Service
subtitle: ''
summary: ''
authors:
- Alberto Barrón-Cedeño
- Lluís Màrquez
- Q. Carlos A. Henríquez
- Lluís Formiga
- Enrique Romero
- Jonathan May
tags: []
categories: []
date: '2013-01-01'
lastmod: 2022-01-27T17:35:10+01:00
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
publishDate: '2022-01-27T16:35:09.941280Z'
publication_types:
- '1'
abstract: Post-editing feedback provided by users of on-line translation services
  offers an excellent opportunity for automatic improvement of statistical machine
  translation (SMT) systems. However, feedback provided by casual users is very noisy,
  and must be automatically filtered in order to identify the potentially useful cases.
  We present a study on automatic feedback filtering in a real weblog collected from
  Reverso.net. We extend and re-annotate a training corpus, define an extended set
  of simple features and approach the problem as a binary classification task, experimenting
  with linear and kernel-based classifiers and feature selection. Results on the feedback
  filtering task show a significant improvement over the majority class, but also
  a precision ceiling around 70-80%. This reflects the inherent difficulty of the
  problem and indicates that shallow features cannot fully capture the semantic nature
  of the problem. Despite the modest results on the filtering task, the classifiers
  are proven effective in an application-based evaluation. The incorporation of a
  filtered set of feedback instances selected from a larger corpus significantly improves
  the performance of a phrase-based SMT system, according to a set of standard evaluation
  metrics.
publication: '*Proceedings of the Twenty-Third International Joint Conference on Artificial
  Intelligence*'
---
