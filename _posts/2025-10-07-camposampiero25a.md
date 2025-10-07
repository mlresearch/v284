---
title: Can Large Reasoning Models do Analogical Reasoning under Perceptual Uncertainty?
openreview: ZcdBwzcBmV
abstract: 'This work presents a first evaluation of two state-of-the-art Large Reasoning
  Models (LRMs), OpenAI’s o3-mini and DeepSeek R1, on analogical reasoning, focusing
  on well-established nonverbal human IQ tests based on Raven’s progressive matrices.
  We benchmark with the I-RAVEN dataset and its extension, I-RAVEN-X, which tests
  the ability to generalize to longer reasoning rules and ranges of the attribute
  values. To assess the influence of visual uncertainties on these symbolic analogical
  reasoning tests, we extend the I-RAVEN-X dataset, which otherwise assumes an oracle
  perception. We adopt a two-fold strategy to simulate this imperfect visual perception:
  1) we introduce confounding attributes which, being sampled at random, do not contribute
  to the prediction of the correct answer of the puzzles, and 2) smooth the distributions
  of the input attributes’ values.  We observe a sharp decline in OpenAI’s o3-mini
  task accuracy, dropping from 86.6% on the original I-RAVEN to just 17.0%—approaching
  random chance—on the more challenging I-RAVEN-X, which increases input length and
  range and emulates perceptual uncertainty. This drop occurred despite spending 3.4x
  more reasoning tokens. A similar trend is also observed for DeepSeek R1: from 80.6%
  to 23.2%. On the other hand, a neuro-symbolic probabilistic abductive model, ARLC,
  that achieves state-of-the-art performances on I-RAVEN, can robustly reason under
  all these out-of-distribution tests, maintaining strong accuracy with only a modest
  accuracy reduction from 98.6% to 88.0%. Our code is available at https://github.com/IBM/raven-large-language-models.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: camposampiero25a
month: 0
tex_title: Can Large Reasoning Models do Analogical Reasoning under Perceptual Uncertainty?
firstpage: 750
lastpage: 776
page: 750-776
order: 750
cycles: false
bibtex_author: Camposampiero, Giacomo and Hersche, Michael and Wattenhofer, Roger
  and Sebastian, Abu and Rahimi, Abbas
author:
- given: Giacomo
  family: Camposampiero
- given: Michael
  family: Hersche
- given: Roger
  family: Wattenhofer
- given: Abu
  family: Sebastian
- given: Abbas
  family: Rahimi
date: 2025-10-07
address:
container-title: Proceedings of The 19th International Conference on Neurosymbolic
  Learning and Reasoning
volume: '284'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 10
  - 7
pdf: https://raw.githubusercontent.com/mlresearch/v284/main/assets/camposampiero25a/camposampiero25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
