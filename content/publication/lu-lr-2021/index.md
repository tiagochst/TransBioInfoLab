---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'LR Hunting: A Random Forest Based Cell–Cell Interaction Discovery Method for
  Single-Cell Gene Expression Data'
subtitle: ''
summary: ''
authors:
- Min Lu
- Yifan Sha
- Tiago C. Silva
- Antonio Colaprico
- Xiaodian Sun
- Yuguang Ban
- Lily Wang
- Brian D. Lehmann
- X. Steven Chen
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
publishDate: '2022-04-13T18:03:41.212593Z'
publication_types:
- '2'
abstract: Cell–cell interactions (CCIs) and cell–cell communication (CCC) are critical
  for maintaining complex biological systems. The availability of single-cell RNA
  sequencing (scRNA-seq) data opens new avenues for deciphering CCIs and CCCs through
  identifying ligand-receptor (LR) gene interactions between cells. However, most
  methods were developed to examine the LR interactions of individual pairs of genes.
  Here, we propose a novel approach named LR hunting which first uses random forests
  (RFs)-based data imputation technique to link the data between different cell types.
  To guarantee the robustness of the data imputation procedure, we repeat the computation
  procedures multiple times to generate aggregated imputed minimal depth index (IMDI).
  Next, we identify significant LR interactions among all combinations of LR pairs
  simultaneously using unsupervised RFs. We demonstrated LR hunting can recover biological
  meaningful CCIs using a mouse cellular indexing of transcriptomes and epitopes by
  sequencing (CITE-seq) dataset and a triple-negative breast cancer scRNA-seq dataset.
publication: '*Frontiers in Genetics*'
links:
- name: URL
  url: https://www.frontiersin.org/article/10.3389/fgene.2021.708835
---
