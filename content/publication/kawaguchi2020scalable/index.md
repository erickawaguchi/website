---
date: "2020-12-10"
external_link: ""
links:
tags:
- Methodology

title: Scalable Algorithms for Large Competing Risks Data
authors:
- Eric S. Kawaguchi
- Jenny I. Shen
- Marc A. Suchard
- Gang Li
url_code: ""
url_pdf: "https://www.tandfonline.com/doi/abs/10.1080/10618600.2020.1841650"
url_slides: ""
url_video: ""
---

This article develops two orthogonal contributions to scalable sparse regression for competing risks time-to-event data. First, we study and accelerate the broken adaptive ridge method (BAR), a surrogate -based iteratively reweighted -penalization algorithm that achieves sparsity in its limit, in the context of the Fine-Gray (1999) proportional subdistributional hazards (PSH) model. In particular, we derive a new algorithm for BAR regression, named cycBAR, that performs cyclic updates of each coordinate using an explicit thresholding formula. The new cycBAR algorithm effectively avoids fitting multiple reweighted -penalizations and thus yields impressive speedups over the original BAR algorithm. Second, we address a pivotal computational issue related to fitting the PSH model. Specifically, the cost of computing the log-pseudo likelihood and its derivatives grows at the rate of  with the sample …