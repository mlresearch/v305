---
title: 'ZipMPC: Compressed Context-Dependent MPC Cost via Imitation Learning'
section: Poster
openreview: R5oDzOZYwb
abstract: The computational burden of model predictive control (MPC) limits its application
  on real-time systems, such as robots, and often requires the use of short prediction
  horizons. This not only affects the control performance, but also increases the
  difficulty of designing MPC cost functions that reflect the desired long-term objective.
  This paper proposes ZipMPC, a method that imitates a long-horizon MPC behaviour
  by learning a compressed and context-dependent cost function for a short-horizon
  MPC. It improves performance over alternative methods, such as approximate explicit
  MPC and automatic cost parameter tuning, in particular in terms of i) optimizing
  the long-term objective; ii) maintaining computational costs comparable to a short-horizon
  MPC; iii) ensuring constraint satisfaction; and iv) generalizing control behaviour
  to environments not observed during training. For this purpose, ZipMPC leverages
  the concept of differentiable MPC with neural networks to propagate gradients of
  the imitation loss through the MPC optimization. We validate our proposed method
  in simulation and real-world experiments on autonomous racing. ZipMPC consistently
  completes laps faster than selected baselines, achieving lap times close to the
  long-horizon MPC baseline. In challenging scenarios where the short-horizon MPC
  baseline fails to complete a lap, ZipMPC is able to do so. In particular, these
  performance gains are also observed on tracks unseen during training.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rickenbach25a
month: 0
tex_title: 'ZipMPC: Compressed Context-Dependent MPC Cost via Imitation Learning'
firstpage: 3115
lastpage: 3136
page: 3115-3136
order: 3115
cycles: false
bibtex_author: Rickenbach, Rahel and Lahoud, Alan and Schaffernicht, Erik and Zeilinger,
  Melanie and Stork, Johannes A.
author:
- given: Rahel
  family: Rickenbach
- given: Alan
  family: Lahoud
- given: Erik
  family: Schaffernicht
- given: Melanie
  family: Zeilinger
- given: Johannes A.
  family: Stork
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
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/rickenbach25a/rickenbach25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
