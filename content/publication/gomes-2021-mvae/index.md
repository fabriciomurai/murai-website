---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Mixture Variational Autoencoder of Boltzmann Machines for Text Processing
subtitle: ''
summary: ''
authors:
- Bruno Guilherme Gomes
- Fabricio Murai
- Olga Goussevskaia
- Ana Paula da Silva
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-08-11T15:11:29-03:00
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
publishDate: '2021-08-11T18:11:29.089991Z'
publication_types:
- '1'
abstract: Variational autoencoders (VAEs) have been successfully used to learn good
  representations in unsupervised settings, especially for image data. More recently,
  mixture variational autoencoders (MVAEs) have been proposed to enhance the representation
  capabilities of VAEs by assuming that data can come from a mixture distribution.
  In this work, we adapt MVAEs for text processing by modeling each component's joint
  distribution of latent variables and document's bag-of-words as a graphical model
  known as the Boltzmann Machine, popular in natural language processing for performing
  well in a number of tasks. The proposed model, MVAE-BM, can learn text representations
  from unlabeled data without requiring pre-trained word embeddings. We evaluate the
  representations obtained by MVAE-BM on six corpora w.r.t. the perplexity metric
  and accuracy on binary and multi-class text classification. Despite its simplicity,
  our results show that MVAE-BM's performance is on par with or superior to that of
  modern deep learning techniques such as BERT and RoBERTa. Last, we show that the
  mapping to mixture components learned by the model lends itself naturally to document
  clustering.
publication: '*Natural Language Processing and Information Systems*'
doi: 10.1007/978-3-030-80599-9_5
---
