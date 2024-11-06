---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Repairs and Breaks Prediction for Deep Neural Networks
subtitle: ''
summary: ''
authors:
- admin-en
- Masanari Kondo
- Lei Ma
- Naoyasu Ubayashi
- Yasutaka Kamei
# tags:
# - Deep neural networks
# - DNN repairing
# - repair and break prediction
categories: []
date: '2024-11-01'
lastmod: 2024-11-06T23:19:47+09:00
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
publishDate: '2024-11-06T14:19:46.907196Z'
publication_types:
- '2'
abstract: 'With the increasing prevalence of software incorporating deep neural networks (DNNs), quality assurance for these software systems has become a crucial concern. To this end, various methods have been proposed to repair the misbehavior of DNNs by modifying their weights. However, these repair methods may not meet the developer’s needs for a given dataset and model. In this study, we build prediction models for repair outcomes (i.e., repairs and breaks) to help determine whether the repair method is likely to work. By using our prediction models, developers and operators of DNNs can decide whether or not to apply a repair method, and if so, which method to use. Our prediction models utilize four metrics as explanatory metrics that represent the confidence or ambiguity in the DNN predictions. We experimented with four repair methods and 10 datasets. The experimental results demonstrate that our prediction models successfully select a repair method that meets developers’ needs in 16 out of 24 cases, resulting in an average time saving of 16.29% compared to the naive method. Based on these results, our prediction models can reduce costs for developers and operators when deciding whether to employ repair methods for real-world applications of DNNs.'
publication: '*ACM Transactions on Software Engineering and Methodology*'
doi: 10.1145/3702983
links:
- name: Code
  url: https://github.com/posl/DNN-repair-break-prediction
---
