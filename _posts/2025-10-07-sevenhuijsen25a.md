---
title: Generating Safety-Critical Automotive C-programs using LLMs with Formal Verification
section: Poster
openreview: xcLrUIeGo3
abstract: We evaluate the feasibility of generating formally verified C code that
  adheres to both functional and non-functional requirements using Large Language
  Models (LLMs) for three real industrial, automotive safety-critical software modules.
  We explore the capabilities of ten LLMs and four prompting techniques — Zero-Shot,
  Zero-Shot Chain-of-Thought, One-Shot, and One-Shot Chain-of-Thought — to generate
  C programs for the three modules. Functional correctness of generated programs is
  assessed through functional verification, and adherence to non-functional requirements
  is evaluated using an industrial static analyzer, along with human evaluation. The
  results demonstrate that it is feasible for LLMs to generate functionally correct
  code, with success rates of 540/800, 59/800, and 46/800 for the three modules. Additionally,
  the generated programs frequently adhere to the defined non-functional requirements.
  In the cases where the LLM-generated programs did not adhere to the non-functional
  requirements, deviations typically involve violations of single-read and single-write
  access patterns or minimal variable scope constraints. These findings highlight
  the promise and limitations of using LLMs to generate industrial safety-critical
  C programs, providing insight into improving automated LLM-based program generation
  in the automotive safety-critical domain.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sevenhuijsen25a
month: 0
tex_title: Generating Safety-Critical Automotive C-programs using LLMs with Formal
  Verification
firstpage: 353
lastpage: 378
page: 353-378
order: 353
cycles: false
bibtex_author: Sevenhuijsen, Merlijn and Patil, Minal Suresh and Nyberg, Mattias and
  Ung, Gustav
author:
- given: Merlijn
  family: Sevenhuijsen
- given: Minal Suresh
  family: Patil
- given: Mattias
  family: Nyberg
- given: Gustav
  family: Ung
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
pdf: https://raw.githubusercontent.com/mlresearch/v284/main/assets/sevenhuijsen25a/sevenhuijsen25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
