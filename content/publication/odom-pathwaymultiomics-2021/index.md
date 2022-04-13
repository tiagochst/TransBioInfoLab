---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'PathwayMultiomics: An R Package for Efficient Integrative Analysis of Multi-Omics
  Datasets With Matched or Un-matched Samples'
subtitle: ''
summary: ''
authors:
- Gabriel J. Odom
- Antonio Colaprico
- Tiago C. Silva
- X. Steven Chen
- Lily Wang
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-04-13T14:03:41-04:00
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
publishDate: '2022-04-13T18:03:41.378971Z'
publication_types:
- '2'
abstract: Recent advances in technology have made multi-omics datasets increasingly
  available to researchers. To leverage the wealth of information in multi-omics data,
  a number of integrative analysis strategies have been proposed recently. However,
  effectively extracting biological insights from these large, complex datasets remains
  challenging. In particular, matched samples with multiple types of omics data measured
  on each sample are often required for multi-omics analysis tools, which can significantly
  reduce the sample size. Another challenge is that analysis techniques such as dimension
  reductions, which extract association signals in high dimensional datasets by estimating
  a few variables that explain most of the variations in the samples, are typically
  applied to whole-genome data, which can be computationally demanding. Here we present
  pathwayMultiomics, a pathway-based approach for integrative analysis of multi-omics
  data with categorical, continuous, or survival outcome variables. The input of pathwayMultiomics
  is pathway p-values for individual omics data types, which are then integrated using
  a novel statistic, the MiniMax statistic, to prioritize pathways dysregulated in
  multiple types of omics datasets. Importantly, pathwayMultiomics is computationally
  efficient and does not require matched samples in multi-omics data. We performed
  a comprehensive simulation study to show that pathwayMultiomics significantly outperformed
  currently available multi-omics tools with improved power and well-controlled false-positive
  rates. In addition, we also analyzed real multi-omics datasets to show that pathwayMultiomics
  was able to recover known biology by nominating biologically meaningful pathways
  in complex diseases such as Alzheimer’s disease.
publication: '*Frontiers in Genetics*'
links:
- name: URL
  url: https://www.frontiersin.org/article/10.3389/fgene.2021.783713
---
