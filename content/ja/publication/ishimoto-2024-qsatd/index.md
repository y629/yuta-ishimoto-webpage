---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Empirical Study on Self-Admitted Technical Debt in Quantum Software
subtitle: ''
summary: ''
authors:
- admin-en
- Yuto Nakamura
- Ryota Katsube
- Naoto Sato
- Hideto Ogawa
- Masanari Kondo
- Yasutaka Kamei
- Naoyasu Ubayashi
tags: []
categories: []
date: '2024-12-01'
lastmod: 2024-09-17T15:22:14+09:00
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
publishDate: '2024-09-17T06:22:14.042870Z'
publication_types:
- '1'
abstract: 'Quantum computers, which utilize the principles of quantum mechanics, are expected to be applied to a wide range of fields. With the advancement of quantum computer development, a lot of quantum software, which enables the operation of quantum computers, has been developed. It has a distinct nature (e.g., superposition and entanglement of qubits) compared to traditional software, leading to the unique challenges of its development. While prior studies have clarified and defined some unique challenges of quantum software, many remain unclear due to limited research.

In this study, we conducted an empirical study of Self-Admitted Technical Debt (SATD) for quantum software. SATD is a type of technical debt, a problem in the code that the developer is aware of. Hence, we conjecture that analyzing SATDs can reveal the unique challenges developers face when developing quantum software. We manually coded 202 comments from the Python® files of the 61 open-source quantum software on GitHub®. The 202 comments correspond to a 95% confidence level with a 5% confidence interval, as in previous studies. The results showed that 88 comments (45.6% of all SATD comments) were quantum-specific SATDs (QSATDs), which require knowledge of quantum computation to repay. Furthermore, we propose a taxonomy for QSATDs. This taxonomy, which consists of four main categories and eight subcategories, classifies QSATDs in terms of quantum-specific aspects such as circuit implementation, backend, and algorithms. Our empirical results are beneficial for quantum software developers, helping them understand implementation areas that require attention. For researchers, our results promote further research, including the exploration of challenges in QSATD repayment.'
publication: '*Proceedings of the 31st Asia-Pacific Software Engineering Conference
  (APSEC)*'

links:
- name: Artifacts
  url: https://zenodo.org/records/12603170
---
