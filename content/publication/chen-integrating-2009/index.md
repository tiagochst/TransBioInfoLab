---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Integrating Biological Knowledge with Gene Expression Profiles for Survival
  Prediction of Cancer
subtitle: ''
summary: ''
authors:
- Xi Chen
- Lily Wang
tags: []
categories: []
date: '2009-02-01'
lastmod: 2022-04-13T14:03:42-04:00
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
publishDate: '2022-04-13T18:03:42.324694Z'
publication_types:
- '2'
abstract: Due to the large variability in survival times between cancer patients and
  the plethora of genes on microarrays unrelated to outcome, building accurate prediction
  models that are easy to interpret remains a challenge. In this paper, we propose
  a general strategy for improving performance and interpretability of prediction
  models by integrating gene expression data with prior biological knowledge. First,
  we link gene identifiers in expression dataset with gene annotation databases such
  as Gene Ontology (GO). Then we construct “supergenes” for each gene category by
  summarizing information from genes related to outcome using a modified principal
  component analysis (PCA) method. Finally, instead of using genes as predictors,
  we use these supergenes representing information from each gene category as predictors
  to predict survival outcome. In addition to identifying gene categories associated
  with outcome, the proposed approach also carries out additional within-category
  selection to select important genes within each gene set. We show, using two real
  breast cancer microarray datasets, that the prediction models constructed based
  on gene sets (or pathway) information outperform the prediction models based on
  expression values of single genes, with improved prediction accuracy and interpretability.
publication: '*Journal of Computational Biology*'
doi: 10.1089/cmb.2008.12TT
links:
- name: URL
  url: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3198940/
---
