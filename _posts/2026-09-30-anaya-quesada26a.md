---
title: Sequential Hypothesis Testing for Black-Box Fairness Audits
openreview: qs0JLOLTUS
abstract: 'Audits of deployed AI systems often have to decide whether a system violates
  a behavioral requirement before the auditor can assemble a large, fixed test set.
  This paper develops a sequential testing framework for black-box fairness auditing.
  We formalize an audit as a pre-specified hypothesis test on a disparity functional
  and instantiate the procedure with Wald’s Sequential Probability Ratio Test (SPRT).
  The framework separates three choices that are often conflated in fairness evaluations:
  the fairness construct to be audited, the tolerance threshold that makes a disparity
  practically or legally material, and the statistical risks that the auditor is willing
  to incur. We evaluate the approach in two studies. In controlled simulations, sequential
  audits detect violations of statistical parity, equal opportunity, and equalized
  odds while, under the studied designs, typically using fewer samples than fixed-sample
  two-proportion tests. In a German Credit case study, the same protocol detects persistent
  disparities in a baseline classifier and in a classifier trained without the sensitive
  attribute, while producing substantially fewer bias flags after demographic-parity
  constrained training. The results show that sequential tests can make fairness audits
  more sample-efficient, but also that nominal error guarantees require careful pre-registration,
  treatment of composite hypotheses, multiple-testing correction, and validation under
  the actual sampling protocol. We further stress-test the procedure on a fair equalized-odds
  model and derive reporting recommendations for finite-budget audits.'
section: Full paper
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: anaya-quesada26a
month: 0
tex_title: Sequential Hypothesis Testing for Black-Box Fairness Audits
firstpage: 51
lastpage: 66
page: 51-66
order: 51
cycles: false
bibtex_author: Anaya-Quesada, Mart\'in and Kountouris, Marios
author:
- given: Martín
  family: Anaya-Quesada
- given: Marios
  family: Kountouris
date: 2026-09-30
address:
container-title: Proceedings of Fifth European Conference on Algorithmic Fairness
volume: '350'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 9
  - 30
pdf: https://raw.githubusercontent.com/mlresearch/v350/main/assets/anaya-quesada26a/anaya-quesada26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
