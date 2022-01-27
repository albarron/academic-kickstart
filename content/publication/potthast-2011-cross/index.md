---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Cross-language plagiarism detection
subtitle: ''
summary: ''
authors:
- Martin Potthast
- Alberto Barrón-Cedeño
- Benno Stein
- Paolo Rosso
tags: []
categories: []
date: '2011-01-01'
lastmod: 2022-01-26T18:49:12+01:00
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
publishDate: '2022-01-27T18:00:28.166556Z'
publication_types:
- '2'
abstract: 'Cross-language plagiarism detection deals with the automatic identification
  and extraction of plagiarism in a multilingual setting. In this setting, a suspicious
  document is given, and the task is to retrieve all sections from the document that
  originate from a large, multilingual document collection. Our contributions in this
  field are as follows: (1) a comprehensive retrieval process for cross-language plagiarism
  detection is introduced, highlighting the differences to monolingual plagiarism
  detection, (2) state-of-the-art solutions for two important subtasks are reviewed,
  (3) retrieval models for the assessment of cross-language similarity are surveyed,
  and, (4) the three models CL-CNG, CL-ESA and CL-ASA are compared. Our evaluation
  is of realistic scale: it relies on 120,000 test documents which are selected from
  the corpora JRC-Acquis and Wikipedia, so that for each test document highly similar
  documents are available in all of the six languages English, German, Spanish, French,
  Dutch, and Polish. The models are employed in a series of ranking tasks, and more
  than 100 million similarities are computed with each model. The results of our evaluation
  indicate that CL-CNG, despite its simple approach, is the best choice to rank and
  compare texts across languages if they are syntactically related. CL-ESA almost
  matches the performance of CL-CNG, but on arbitrary pairs of languages. CL-ASA works
  best on \"exact\" translations but does not generalize well.'
publication: '*Language Resources and Evaluation*'
doi: 10.1007/s10579-009-9114-z
---
