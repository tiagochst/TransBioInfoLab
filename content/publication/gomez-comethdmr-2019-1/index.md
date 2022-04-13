---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'coMethDMR: accurate identification of co-methylated and differentially methylated
  regions in epigenome-wide association studies with continuous phenotypes'
subtitle: ''
summary: ''
authors:
- Lissette Gomez
- Gabriel J Odom
- Juan I Young
- Eden R Martin
- Lizhong Liu
- Xi Chen
- Anthony J Griswold
- Zhen Gao
- Lanyu Zhang
- Lily Wang
tags: []
categories: []
date: '2019-09-01'
lastmod: 2022-04-13T17:39:52-04:00
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
publishDate: '2022-04-13T21:39:51.516753Z'
publication_types:
- '2'
abstract: Recent technology has made it possible to measure DNA methylation profiles
  in a cost-effective and comprehensive genome-wide manner using array-based technology
  for epigenome-wide association studies. However, identifying differentially methylated
  regions (DMRs) remains a challenging task because of the complexities in DNA methylation
  data. Supervised methods typically focus on the regions that contain consecutive
  highly significantly differentially methylated CpGs in the genome, but may lack
  power for detecting small but consistent changes when few CpGs pass stringent significance
  threshold after multiple comparison. Unsupervised methods group CpGs based on genomic
  annotations first and then test them against phenotype, but may lack specificity
  because the regional boundaries of methylation are often not well defined. We present
  coMethDMR, a flexible, powerful, and accurate tool for identifying DMRs. Instead
  of testing all CpGs within a genomic region, coMethDMR carries out an additional
  step that selects co-methylated sub-regions first. Next, coMethDMR tests association
  between methylation levels within the sub-region and phenotype via a random coefficient
  mixed effects model that models both variations between CpG sites within the region
  and differential methylation simultaneously. coMethDMR offers well-controlled Type
  I error rate, improved specificity, focused testing of targeted genomic regions,
  and is available as an open-source R package.
publication: '*Nucleic Acids Research*'
doi: 10.1093/nar/gkz590
links:
- name: URL
  url: https://doi.org/10.1093/nar/gkz590
---
