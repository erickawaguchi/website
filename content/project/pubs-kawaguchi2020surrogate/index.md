---
title: "A surrogate $l_0$ sparse Cox's regression with applications to sparse high‐dimensional massive sample size time‐to‐event data"
tags: 
- pubs
authors:
date: "2019-02-11T00:00:00Z"
doi: "10.1002/sim.8438"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
#publication: In *Source Themes Conference*
#publication_short: In *STC*

abstract: Sparse high‐dimensional massive sample size (sHDMSS) time‐to‐event data present multiple challenges to quantitative researchers as most current sparse survival regression methods and software will grind to a halt and become practically inoperable. This paper develops a scalable $l_0$‐based sparse Cox regression tool for right‐censored time‐to‐event data that easily takes advantage of existing high performance implementation of $l_2$‐penalized regression method for sHDMSS time‐to‐event data. Specifically, we extend the $l_0$‐based broken adaptive ridge (BAR) methodology to the Cox model, which involves repeatedly performing reweighted $l_2$‐penalized regression. We rigorously show that the resulting estimator for the Cox model is selection consistent, oracle for parameter estimation, and has a grouping property for highly correlated covariates. Furthermore, we implement our BAR method in an R package for sHDMSS time‐to‐event data by leveraging existing efficient algorithms for massive $l_2$‐penalized Cox regression. We evaluate the BAR Cox regression method by extensive simulations and illustrate its application on an sHDMSS time‐to‐event data from the National Trauma Data Bank with hundreds of thousands of observations and tens of thousands sparsely represented covariates.

# Summary. An optional shortened abstract.
summary: Sparse high‐dimensional massive sample size (sHDMSS) time‐to‐event data present multiple challenges to quantitative researchers as most current sparse survival regression methods and software will grind to a halt and become practically inoperable. This paper develops a scalable $l_0$‐based sparse Cox regression tool for right‐censored time‐to‐event data that easily takes advantage of existing high performance implementation of $l_2$‐penalized regression method for sHDMSS time‐to‐event data.

external_link: https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.8438
#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.8438
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'
---