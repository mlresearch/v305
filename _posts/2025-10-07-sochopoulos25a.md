---
title: Fast Flow-based Visuomotor Policies via Conditional Optimal Transport Couplings
section: Poster
openreview: Nt4LmgZ7v9
abstract: Diffusion and flow matching policies have recently demonstrated remarkable
  performance in robotic applications by accurately capturing multimodal robot trajectory
  distributions. However, their computationally expensive inference, due to the numerical
  integration of an ODE or SDE, limits their applicability as real-time controllers
  for robots. We introduce a methodology that utilizes conditional Optimal Transport
  couplings between noise and samples to enforce straight solutions in the flow ODE
  for robot action generation tasks. We show that naively coupling noise and samples
  fails in conditional tasks and propose incorporating condition variables into the
  coupling process to improve few-step performance. The proposed few-step policy achieves
  a 4% higher success rate with a 10$\times$ speed-up compared to Diffusion Policy
  on a diverse set of simulation tasks. Moreover, it produces high-quality and diverse
  action trajectories within 1-2 steps on a set of real-world robot tasks. Our method
  also retains the same training complexity as Diffusion Policy and vanilla Flow Matching,
  in contrast to distillation-based approaches.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sochopoulos25a
month: 0
tex_title: Fast Flow-based Visuomotor Policies via Conditional Optimal Transport Couplings
firstpage: 3357
lastpage: 3377
page: 3357-3377
order: 3357
cycles: false
bibtex_author: Sochopoulos, Andreas and Malkin, Nikolay and Tsagkas, Nikolaos and
  Moura, Joao and Gienger, Michael and Vijayakumar, Sethu
author:
- given: Andreas
  family: Sochopoulos
- given: Nikolay
  family: Malkin
- given: Nikolaos
  family: Tsagkas
- given: Joao
  family: Moura
- given: Michael
  family: Gienger
- given: Sethu
  family: Vijayakumar
date: 2025-10-07
address:
container-title: Proceedings of The 9th Conference on Robot Learning
volume: '305'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 10
  - 7
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/sochopoulos25a/sochopoulos25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
