---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'PAFL: Probabilistic Automaton-based Fault Localization for Recurrent Neural
  Networks'
subtitle: ''
summary: ''
authors:
- admin
- Masanari Kondo
- Naoyasu Ubayashi
- Yasutaka Kamei
tags: []
categories: []
date: '2023-03-01'
lastmod: 2023-08-04T11:27:37+09:00
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
publishDate: '2023-11-05T16:35:32.335175Z'
publication_types:
- '2'
abstract: 'Context:
If deep learning models in safety–critical systems misbehave, serious accidents may occur. Previous studies have proposed approaches to overcome such misbehavior by detecting and modifying the responsible faulty parts in deep learning models. For example, fault localization has been applied to deep neural networks to detect neurons that cause misbehavior.

Objective:
However, such approaches are not applicable to deep learning models that have internal states, which change dynamically based on the input data samples (e.g., recurrent neural networks (RNNs)). Hence, we propose a new fault localization approach to be applied to RNNs.

Methods:
We propose probabilistic automaton-based fault localization (PAFL). PAFL enables developers to detect faulty parts even in RNNs by computing suspiciousness scores with fault localization using 
-grams. We convert RNNs into probabilistic finite automata (PFAs) and localize faulty sequences of state transitions on PFAs. To consider various sequences and to detect faulty ones more precisely, we use 
-grams inspired by natural language processing. Additionally, we distinguish data samples related to the misbehavior to evaluate PAFL. We also propose a novel suspiciousness score, average 
-gram suspiciousness (ANS) score, based on 
-grams to distinguish data samples. We evaluate PAFL and ANS scores on eight publicly available datasets on three RNN variants: simple recurrent neural network, gated recurrent units, and long short-term memory.

Results:
The experiment demonstrates that ANS scores identify faulty parts of RNNs when 
 is greater than one. Moreover, PAFL is statistically significantly better and has large effect sizes compared to state-of-the-art fault localization in terms of distinguishing data samples related to the misbehavior. Specifically, PAFL is better in 66.74% of the experimental settings.

Conclusion:
The results demonstrate that PAFL can be used to detect faulty parts in RNNs. Hence, in future studies, PAFL can be used as a baseline for fault localization in RNNs.'

publication: '*Information and Software Technology*'

links:
- name: Website (Open Access)
  url: https://doi.org/10.1016/j.infsof.2022.107117
- name: Code
  url: https://github.com/posl/PAFL-replication
---
