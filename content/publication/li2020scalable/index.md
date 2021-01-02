---
date: "2020-12-17"
external_link: ""
links:
tags:
- Methodology

title: A scalable surrogate L0 sparse regression method for generalized linear models with applications to large scale data
authors:
- Ning Li
- Xiaoling Peng
- Eric Kawaguchi
- Marc A. Suchard
- Gang Li
url_code: ""
url_pdf: "https://www.sciencedirect.com/science/article/abs/pii/S037837582030135X"
url_slides: ""
url_video: ""
---

This paper rigorously studies large sample properties of a surrogate L 0 penalization method via iteratively performing reweighted L 2 penalized regressions for generalized linear models and develop a scalable implementation of the method for sparse high dimensional massive sample size (sHDMSS) data. We show that for generalized linear models, the limit of the algorithm, referred to as the broken adaptive ridge (BAR) estimator, is consistent for variable selection, enjoys an oracle property for parameter estimation, and possesses a grouping property for highly correlated covariates. We further demonstrate that by taking advantage of an existing efficient implementation of massive L 2-penalized generalized linear models, the proposed BAR method can be conveniently implemented for sHDMSS data. An illustration is given using a large sHDMSS data from the Truven MarketScan Medicare (MDCR) database to …