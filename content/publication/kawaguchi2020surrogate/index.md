---
date: "2020-03-15"
external_link: ""
links:
tags:
- Methodology

title: A surrogate L0 sparse Cox's regression with applications to sparse high‐dimensional massive sample size time‐to‐event data
authors:
- Eric S. Kawaguchi
- Marc A. Suchard
- Zhenqiu Liu
- Gang Li
url_code: ""
url_pdf: "https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.8438"
url_slides: ""
url_video: ""
---

Sparse high‐dimensional massive sample size (sHDMSS) time‐to‐event data present multiple challenges to quantitative researchers as most current sparse survival regression methods and software will grind to a halt and become practically inoperable. This paper develops a scalable ℓ0‐based sparse Cox regression tool for right‐censored time‐to‐event data that easily takes advantage of existing high performance implementation of ℓ2‐penalized regression method for sHDMSS time‐to‐event data. Specifically, we extend the ℓ0‐based broken adaptive ridge (BAR) methodology to the Cox model, which involves repeatedly performing reweighted ℓ2‐penalized regression. We rigorously show that the resulting estimator for the Cox model is selection consistent, oracle for parameter estimation, and has a grouping property for highly correlated covariates. Furthermore, we implement our BAR method in an R package …