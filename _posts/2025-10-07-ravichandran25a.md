---
title: Distilling On-device Language Models for Robot Planning with Minimal Human
  Intervention
section: Poster
openreview: 93bWCbhXJR
abstract: Large language models (LLMs) provide robots with powerful contextual reasoning
  abilities and a natural human interface. Yet, current LLM-enabled robots typically
  depend on cloud-hosted models, limiting their usability in environments with unreliable
  communication infrastructure, such as outdoor or industrial settings. We present
  PRISM, a framework for distilling small language model (SLM)-enabled robot planners
  that run on-device with minimal human supervision. Starting from an existing LLM-enabled
  planner, PRISM automatically synthesizes diverse tasks and environments, elicits
  plans from the LLM, and uses this synthetic dataset to distill a compact SLM as
  a drop-in replacement of the source model. We apply PRISM to three LLM-enabled planners
  for mapping and exploration, manipulation, and household assistance, and we demonstrate
  that PRISM improves the performance of Llama-3.2-3B from 10-20% of GPT-4o’s performance
  to over 93% - using only synthetic data. We further demonstrate that the distilled
  planners generalize across heterogeneous robotic platforms (ground and aerial) and
  diverse environments (indoor and outdoor). We release all software, trained models,
  and datasets to promote reproducibility and follow-up work.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ravichandran25a
month: 0
tex_title: Distilling On-device Language Models for Robot Planning with Minimal Human
  Intervention
firstpage: 4859
lastpage: 4884
page: 4859-4884
order: 4859
cycles: false
bibtex_author: Ravichandran, Zachary and Hounie, Ignacio and Cladera, Fernando and
  Ribeiro, Alejandro and Pappas, George J. and Kumar, Vijay
author:
- given: Zachary
  family: Ravichandran
- given: Ignacio
  family: Hounie
- given: Fernando
  family: Cladera
- given: Alejandro
  family: Ribeiro
- given: George J.
  family: Pappas
- given: Vijay
  family: Kumar
date: 2025-10-07
address:
container-title: Proceedings of The 8th Conference on Robot Learning
volume: '305'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 10
  - 7
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/ravichandran25a/ravichandran25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
