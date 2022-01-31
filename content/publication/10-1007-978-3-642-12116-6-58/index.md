---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Word Length n-Grams for Text Re-use Detection
subtitle: ''
summary: ''
authors:
- Alberto Barrón-Cedeño
- Chiara Basile
- Mirko Degli Esposti
- Paolo Rosso
tags: []
categories: []
date: '2010-01-01'
lastmod: 2022-01-31T16:38:36+01:00
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
publishDate: '2022-01-31T15:58:11.962331Z'
publication_types:
- '1'
abstract: 'The automatic detection of shared content in written documents --which
  includes text reuse and its unacknowledged commitment, plagiarism-- has become an
  important problem in Information Retrieval. This task requires exhaustive comparison
  of texts in order to determine how similar they are. However, such comparison is
  impossible in those cases where the amount of documents is too high. Therefore,
  we have designed a model for the proper pre-selection of closely related documents
  in order to perform the exhaustive comparison afterwards. We use a similarity measure
  based on word-level n-grams, which proved to be quite effective in many applications
  As this approach becomes normally impracticable for real-world large datasets, we
  propose a method based on a preliminary word-length encoding of texts, substituting
  a word by its length, providing three important advantages: (i) being the alphabet
  of the documents reduced to nine symbols, the space needed to store n-gram lists
  is reduced; (ii) computation times are decreased; and (iii) length n-grams can be
  represented in a trie, allowing a more flexible and fast comparison. We experimentally
  show, on the basis of the perplexity measure, that the noise introduced by the length
  encoding does not decrease importantly the expressiveness of the text. The method
  is then tested on two large datasets of co-derivatives and simulated plagiarism.'
publication: '*Computational Linguistics and Intelligent Text Processing*'
---
