---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Supervised principal component analysis for gene set enrichment of microarray
  data with continuous or survival outcomes
subtitle: ''
summary: ''
authors:
- Xi Chen
- Lily Wang
- Jonathan D. Smith
- Bing Zhang
tags: []
categories: []
date: '2008-11-01'
lastmod: 2022-04-14T10:57:43-04:00
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
publishDate: '2022-04-14T14:57:43.196569Z'
publication_types:
- '2'
abstract: 'Motivation: Gene set analysis allows formal testing of subtle but coordinated
  changes in a group of genes, such as those defined by Gene Ontology (GO) or KEGG
  Pathway databases. We propose a new method for gene set analysis that is based on
  principal component analysis (PCA) of genes expression values in the gene set. PCA
  is an effective method for reducing high dimensionality and capture variations in
  gene expression values. However, one limitation with PCA is that the latent variable
  identified by the first PC may be unrelated to outcome., Results: In the proposed
  supervised PCA (SPCA) model for gene set analysis, the PCs are estimated from a
  selected subset of genes that are associated with outcome. As outcome information
  is used in the gene selection step, this method is supervised, thus called the Supervised
  PCA model. Because of the gene selection step, test statistic in SPCA model can
  no longer be approximated well using t-distribution. We propose a two-component
  mixture distribution based on Gumbel exteme value distributions to account for the
  gene selection step. We show the proposed method compares favorably to currently
  available gene set analysis methods using simulated and real microarray data., Software:
  The R code for the analysis used in this article are available upon request, we
  are currently working on implementing the proposed method in an R package., Contact:
  chenx3@ccf.org.'
publication: '*Bioinformatics*'
doi: 10.1093/bioinformatics/btn458
links:
- name: URL
  url: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2732277/
---
