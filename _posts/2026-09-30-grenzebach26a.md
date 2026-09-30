---
title: Probing Protected Attributes within General-Purpose LLMs for Hiring
openreview: 4aBhY4hVcQ
abstract: General-purpose Large Language Models (LLM) applications in human resource
  workflows are primarily driven by the need for objectivity and efficiency. However,
  a significant gap exists between enterprise-level AI and the consumer-grade ”black-box”
  services frequently utilized by small and medium-sized enterprises (SMEs), raising
  critical questions regarding algorithmic consistency and fairness. This paper utilizes
  the IN-OUT framework, a stimulus-response methodology derived from the cognitive
  sciences, to empirically audit the behavior of one popular LLM. We employ a 2 $\times$
  2 factorial design to analyze how the model responds to protected attributes (including
  gender, age, and nationality) across five varying stimulus volumes ranging from
  K = 16 to 12,000 curricula vitae (CVs). The findings reveal that while the model
  demonstrates acute sensitivity to objective professional suitability demographic
  bias does not operate as a static constant. Instead, bias manifests non-linearly
  as a context-dependent interaction effect. While the model exhibited robust neutrality
  at extreme low and high stimulus volumes (K = 16 and K = 12,000) significant gender
  and age-related structural breakdowns occurred at mid-range context densities (K
  = 3,000 and K = 6,000). In contrast, evaluations regarding nationality remained
  robustly equitable across all stimulus volumes. Furthermore, a multi-account audit
  across N= 11 independent user sessions confirms that while stochastic noise significantly
  shifts absolute scoring for candidate filtering baselines, the underlying discriminatory
  configurations remain structurally invariant (r > 0.99) even at the smallest sample
  sizes. These results suggest that absolute score thresholds for candidate filtering
  are highly unreliable and that latent biases can trigger unpredictably as context
  windows approach saturation limits. The study concludes with practical implications
  for digital governance and the necessity of high-volume algorithmic stress tests
  to ensure non-discriminatory HR selection under the regulatory frameworks of the
  EU AI Act.
section: Full paper
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: grenzebach26a
month: 0
tex_title: Probing Protected Attributes within General-Purpose LLMs for Hiring
firstpage: 372
lastpage: 385
page: 372-385
order: 372
cycles: false
bibtex_author: Grenzebach, Jan and Rad\"untz, Thea
author:
- given: Jan
  family: Grenzebach
- given: Thea
  family: Radüntz
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
pdf: https://raw.githubusercontent.com/mlresearch/v350/main/assets/grenzebach26a/grenzebach26a.pdf
extras:
- label: Supplementary PDF
  link: https://raw.githubusercontent.com/mlresearch/v350/main/assets/assets/grenzebach26a/grenzebach26a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
