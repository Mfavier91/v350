---
title: Sequential Fairness Auditing with Limited Output Access
openreview: Kox7xFpTd7
abstract: External evaluations are becoming increasingly central to the governance
  of AI systems. In practice, however, independent auditors often have limited access
  to deployed models and must rely on query-based interactions. Most existing fairness
  evaluation methods assume static datasets and fixed-sample statistical tests, making
  them poorly suited to real-world auditing scenarios in which evidence must be collected
  sequentially under query constraints. In this work, we formulate fairness auditing
  as a tolerance-aware sequential hypothesis-testing problem under limited model output
  access. We develop a sequential generalized likelihood-ratio framework that allows
  auditors to accumulate evidence from a finite audit pool and stop once sufficient
  support for compliance or violation has been obtained. The framework is instantiated
  for decision-based Statistical Parity and Equal Opportunity audits, and extended
  to score- and logit-based proxy audits when richer observables are available. Our
  results show that both the fairness metric and the level of model access significantly
  affect audit efficiency, and that the benefits of richer output information are
  not uniform across auditing settings. In particular, richer outputs can substantially
  reduce the number of queries required for some fairness metrics and operating regimes,
  while offering limited gains in near-threshold cases. This work provides a practical
  statistical framework for sequential fairness auditing under realistic deployment
  constraints.
section: Full paper
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: pitsiorlas26a
month: 0
tex_title: Sequential Fairness Auditing with Limited Output Access
firstpage: 254
lastpage: 270
page: 254-270
order: 254
cycles: false
bibtex_author: Pitsiorlas, Ioannis and Sourla, Martha-Vasiliki and Kountouris, Marios
author:
- given: Ioannis
  family: Pitsiorlas
- given: Martha-Vasiliki
  family: Sourla
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
pdf: https://raw.githubusercontent.com/mlresearch/v350/main/assets/pitsiorlas26a/pitsiorlas26a.pdf
extras:
- label: Supplementary PDF
  link: https://raw.githubusercontent.com/mlresearch/v350/main/assets/assets/pitsiorlas26a/pitsiorlas26a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
