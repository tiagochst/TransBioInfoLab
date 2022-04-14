---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Statistical Analysis of Patient-Specific Pathway Activities via Mixed Models
subtitle: ''
summary: ''
authors:
- Lily Wang
- Xi Chen
- Bing Zhang
tags: []
categories: []
date: '2012-01-01'
lastmod: 2022-04-14T10:57:40-04:00
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
publishDate: '2022-04-14T14:57:39.736714Z'
publication_types:
- '2'
abstract: In the study of complex diseases, a major challenge is disease heterogeneity,
  where the dysregulation of different pathways often lead to similar disease phenotypes.
  As a result, a given pathway could be differentially expressed with respect to controls
  for some patients, but not for others. Therefore, to develop successful personalized
  treatment regime, in addition to identifying disease relevant pathways for the entire
  patient group, it’s also important to test if a particular pathway is dysregulated
  for an individual patient. To this end, we compare pathway gene expression profile
  for a particular individual in the patient group to the “norm” (or standard) established
  by a group of control patients. We studied statistical analysis of patient-specific
  pathway activities under the mixed models framework. Using gene expression dataset
  with realistic correlation patterns, we showed the proposed hypothesis testing procedure
  had false positive rate (type I error) as expected. In addition, we illustrated
  the proposed methodology using a Type 2 Diabetes dataset. Our results showed a previously
  diabetes associated pathway was only differentially expressed (relative to the control
  group) in less than 30% of the diabetes patients, which provided an explanation
  for the moderate group level statistical significance seen in a previous study.
  This result also suggested targeting this particular pathway would likely be beneficial
  for only 30% of the patients. In addition to the case-control study we have illustrated,
  this model can be easily extended to handle more complex designs with additional
  covariates and multiple sources of variations. Moreover, the proposed model operates
  within a well-established statistical framework and can be implemented in common
  statistical packages.
publication: '*Journal of biometrics & biostatistics*'
doi: 10.4172/2155-6180.S8-001
links:
- name: URL
  url: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3793893/
---
