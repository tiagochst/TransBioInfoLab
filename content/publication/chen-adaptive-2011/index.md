---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Adaptive Elastic-Net Sparse Principal Component Analysis for Pathway Association
  Testing
subtitle: ''
summary: ''
authors:
- Xi Chen
tags: []
categories: []
date: '2011-10-01'
lastmod: 2022-04-14T10:57:42-04:00
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
publishDate: '2022-04-14T14:57:41.618801Z'
publication_types:
- '2'
abstract: 'Pathway or gene set analysis has become an increasingly popular approach
  for analyzing high-throughput biological experiments such as microarray gene expression
  studies. The purpose of pathway analysis is to identify differentially expressed
  pathways associated with outcomes. Important challenges in pathway analysis are
  selecting a subset of genes contributing most to association with clinical phenotypes
  and conducting statistical tests of association for the pathways efficiently. We
  propose a two-stage analysis strategy: (1) extract latent variables representing
  activities within each pathway using a dimension reduction approach based on adaptive
  elastic-net sparse principal component analysis; (2) integrate the latent variables
  with the regression modeling framework to analyze studies with different types of
  outcomes such as binary, continuous or survival outcomes. Our proposed approach
  is computationally efficient. For each pathway, because the latent variables are
  estimated in an unsupervised fashion without using disease outcome information,
  in the sample label permutation testing procedure, the latent variables only need
  to be calculated once rather than for each permutation resample. Using both simulated
  and real datasets, we show our approach performed favorably when compared with five
  other currently available pathway testing methods.'
publication: '*Statistical Applications in Genetics and Molecular Biology*'
doi: 10.2202/1544-6115.1697
links:
- name: URL
  url: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3215429/
---
