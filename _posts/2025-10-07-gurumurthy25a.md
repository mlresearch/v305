---
title: 'DEQ-MPC : Deep Equilibrium Model Predictive Control'
section: Poster
openreview: zQXurgHUVX
abstract: Incorporating task-specific priors within a policy or network architecture
  is crucial for enhancing safety and improving representation and generalization
  in robotic control problems. Differentiable Model Predictive Control (MPC) layers
  have proven effective for embedding these priors, such as constraints and cost functions,
  directly within the architecture, enabling end-to-end training. However, current
  methods often treat the solver and the neural network as separate, independent entities,
  leading to suboptimal integration. In this work, we propose a novel approach that
  co-develops the solver and architecture unifying the optimization solver and network
  inference problems. Specifically, we formulate this as a \textit{joint fixed-point
  problem} over the coupled network outputs and necessary conditions of the optimization
  problem. We solve this problem in an iterative manner where we alternate between
  network forward passes and optimization iterations. Through extensive ablations
  in various robotic control tasks, we demonstrate that our approach results in richer
  representations and more stable training, while naturally accommodating warm starting,
  a key requirement for MPC.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gurumurthy25a
month: 0
tex_title: 'DEQ-MPC : Deep Equilibrium Model Predictive Control'
firstpage: 961
lastpage: 980
page: 961-980
order: 961
cycles: false
bibtex_author: Gurumurthy, Swaminathan and Nguyen, Khai and Bishop, Arun L and Kolter,
  J Zico and Manchester, Zachary
author:
- given: Swaminathan
  family: Gurumurthy
- given: Khai
  family: Nguyen
- given: Arun L
  family: Bishop
- given: J Zico
  family: Kolter
- given: Zachary
  family: Manchester
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
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/gurumurthy25a/gurumurthy25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
