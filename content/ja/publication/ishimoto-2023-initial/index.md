---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Initial Analysis of Repair and Side-effect Prediction for Neural Networks
subtitle: ''
summary: ''
authors:
- admin-en
- Ken Matsui
- Masanari Kondo
- Naoyasu Ubayashi
- Yasutaka Kamei
tags: []
categories: []
date: '2023-05-01'
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
publishDate: '2023-08-04T03:33:21.409020Z'
publication_types:
- '1'
abstract: 'With the prevalence of software systems adopting neural network models, the quality assurance of these systems has become crucial. Hence, various studies have proposed repairing methods for neural network models so far to improve the quality of the models. While these methods are evaluated by researchers, it is difficult to tell whether they succeed in all models and datasets (i.e., all developers’ environments). Because these methods require many resources, such as execution times, failing to repair neural networks would cost developers their resources. Hence, if developers can know whether repairing methods succeed before adopting them, they could avoid wasting their resources. This paper proposes prediction models that predict whether repairing methods succeed in repairing neural networks using a small resource. Our prediction models predict repairs and side-effects of repairing methods, respectively. We evaluated our prediction models on a state-of-the-art repairing method Arachne on three datasets, Fashion-MNIST, CIFAR-10, and GTSRB, and found our prediction models achieved high performance, an average ROC-AUC of 0.931 and an average f1score of 0.880 for the side-effects and an average ROC-AUC of 0.768 and an average f1-score of 0.725 for the repairs.'

publication: '*Proceedings of the 2nd International Conference on AI Engineering--Software
  Engineering for AI (CAIN)*'

links: 
- name: Proceedings
  url: https://ieeexplore.ieee.org/abstract/document/10164756
- name: PDF
  url: https://posl.ait.kyushu-u.ac.jp/~ishimoto/pdfs/cain_short_paper.pdf
- name: Code
  url: https://zenodo.org/record/7329278

---