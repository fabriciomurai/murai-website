---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Selective harvesting over networks
subtitle: ''
summary: ''
authors:
- Fabricio Murai
- Diogo Rennó
- Bruno Ribeiro
- Gisele L Pappa
- Don Towsley
- Krista Gile
tags: []
categories: []
date: '2018-01-01'
lastmod: 2021-08-11T15:11:23-03:00
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
publishDate: '2021-08-11T18:11:23.664472Z'
publication_types:
- '2'
abstract: 'Active search on graphs focuses on collecting certain labeled nodes (targets)
  given global knowledge of the network topology and its edge weights (encoding pairwise
  similarities) under a query budget constraint. However, in most current networks,
  nodes, network topology, network size, and edge weights are all initially unknown.
  In this work we introduce selective harvesting, a variant of active search where
  the next node to be queried must be chosen among the neighbors of the current queried
  node set; the available training data for deciding which node to query is restricted
  to the subgraph induced by the queried set (and their node attributes) and their
  neighbors (without any node or edge attributes). Therefore, selective harvesting
  is a sequential decision problem, where we must decide which node to query at each
  step. A classifier trained in this scenario can suffer from what we call a tunnel
  vision effect: without any recourse to independent sampling, the urge to only query
  promising nodes forces classifiers to gather increasingly biased training data,
  which we show significantly hurts the performance of active search methods and standard
  classifiers. We demonstrate that it is possible to collect a much larger set of
  targets by using multiple classifiers, not by combining their predictions as a weighted
  ensemble, but switching between classifiers used at each step, as a way to ease
  the tunnel vision effect. We discover that switching classifiers collects more targets
  by (a) diversifying the training data and (b) broadening the choices of nodes that
  can be queried in the future. This highlights an exploration, exploitation, and
  diversification trade-off in our problem that goes beyond the exploration and exploitation
  duality found in classic sequential decision problems. Based on these observations
  we propose D$$^3$$TS, a method based on multi-armed bandits for non-stationary stochastic
  processes that enforces classifier diversity, which outperforms all competing methods
  on five real network datasets in our evaluation and exhibits comparable performance
  on the other two.'
publication: '*Data Mining and Knowledge Discovery*'
url_pdf: https://doi.org/10.1007/s10618-017-0523-0
doi: 10.1007/s10618-017-0523-0
---
