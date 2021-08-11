---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Characterizing Directed and Undirected Networks via Multidimensional Walks
  with Jumps
subtitle: ''
summary: ''
authors:
- Fabricio Murai
- Bruno Ribeiro
- Don Towlsey
- Pinghui Wang
tags:
- '"Complex networks"'
- '"directed networks"'
- '"graph sampling"'
- '"random walks"'
categories: []
date: '2019-01-01'
lastmod: 2021-08-11T15:11:25-03:00
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
publishDate: '2021-08-11T18:11:25.178085Z'
publication_types:
- '2'
abstract: Estimating distributions of node characteristics (labels) such as number
  of connections or citizenship of users in a social network via edge and node sampling
  is a vital part of the study of complex networks. Due to its low cost, sampling
  via a random walk (RW) has been proposed as an attractive solution to this task.
  Most RW methods assume either that the network is undirected or that walkers can
  traverse edges regardless of their direction. Some RW methods have been designed
  for directed networks where edges coming into a node are not directly observable.
  In this work, we propose Directed Unbiased Frontier Sampling (DUFS), a sampling
  method based on a large number of coordinated walkers, each starting from a node
  chosen uniformly at random. It applies to directed networks with invisible incoming
  edges because it constructs, in real time, an undirected graph consistent with the
  walkers trajectories, and its use of random jumps to prevent walkers from being
  trapped. DUFS generalizes previous RW methods and is suited for undirected networks
  and to directed networks regardless of in-edge visibility. We also propose an improved
  estimator of node label distribution that combines information from initial walker
  locations with subsequent RW observations. We evaluate DUFS, compare it to other
  RW methods, investigate the impact of its parameters on estimation accuracy and
  provide practical guidelines for choosing them. In estimating out-degree distributions,
  DUFS yields significantly better estimates of the head of the distribution than
  other methods, while matching or exceeding estimation accuracy of the tail. Last,
  we show that DUFS outperforms uniform sampling when estimating distributions of
  node labels of the top 10% largest degree nodes, even when sampling a node uniformly
  has the same cost as RW steps.
publication: '*ACM Trans. Knowl. Discov. Data*'
url_pdf: https://doi.org/10.1145/3299877
doi: 10.1145/3299877
---
