---
title: TNBCtype

event_url: https://cbc.app.vumc.org/tnbc/index.php

summary: Triple negative breast cancer (TNBC) is a heterogeneous breast cancer group, and identification of its subtypes is essential for understanding the biological characteristics and clinical behaviors of TNBC as well as for developing personalized treatments.


# Schedule page publish date (NOT talk date).
publishDate: '2012-01-30T00:00:00Z'

authors: [Xi Chen, Jiang Li, William H. Gray, Brian D. Lehmann, Joshua A. Bauer, Yu Shyr, Jennifer A. Pietenpol]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

Triple negative breast cancer (TNBC) is a heterogeneous breast cancer group, and identification of its subtypes is essential for understanding the biological characteristics and clinical behaviors of TNBC as well as for developing personalized treatments. Based on 3,247 gene expression profiles from 21 breast cancer data sets, we discovered six TNBC subtypes including 2 basal-like (BL1 and BL2), an immunomodulatory (IM), a mesenchymal (M), a mesenchymal stem–like (MSL), and a luminal androgen receptor (LAR) subtype from 587 TNBC samples with unique gene expression patterns and ontologies. Cell line models representing each of the TNBC subtypes also displayed different sensitivities to targeted therapeutic agents. 

It is important to classify the TNBC into subtypes for further genomic research and clinical applications. We developed a web-based prediction tool for candidate TNBC samples using our gene expression meta data and classification methods. Given a gene expression data matrix, this tool will display for each candidate sample the predicted subtype, the corresponding correlation coefficient, and the permutation p-value. 

The input data is a genome-wide gene expression matrix in a .csv file (please check the help section for details). We highly recommend pre-processing and normalizing the raw data for TNBC samples only. The distinctions between TNBC subtypes are relatively subtle compared with the dramatic difference between TNBC and ER positive breast cancer samples at the transcriptome level. If we normalize TNBC gene expressions with the ER positive samples, the gene expression signals driven by ER could disturb the TNBC gene expression normalization, thus affecting the final prediction results. Thus we have implemented a quality control step in TNBCtype program, to identify ER-positive samples. In the event that a sample does not pass the ER-filter, the user will be notified to remove the possible ER-positive sample and redo the normalization procedures.

