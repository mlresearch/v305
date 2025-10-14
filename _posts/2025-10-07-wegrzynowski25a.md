---
title: 'Beyond Constant Parameters: Hyper Prediction Models and HyperMPC'
section: Poster
openreview: 8v0mlyKk5q
abstract: Model Predictive Control (MPC) is among the most widely adopted and reliable
  methods for robot control, relying critically on an accurate dynamics model. However,
  existing dynamics models used in the gradient-based MPC are limited by computational
  complexity and state representation. To address this limitation, we propose the
  Hyper Prediction Model (HyperPM) - a novel approach in which we project the unmodeled
  dynamics onto a time-dependent dynamics model. This time-dependency is captured
  through time-varying model parameters, whose evolution over the MPC prediction horizon
  is learned using a neural network. Such formulation preserves the computational
  efficiency and robustness of the base model while equipping it with the capacity
  to anticipate previously unmodeled phenomena. We evaluated the proposed approach
  on several challenging systems, including real-world F1TENTH autonomous racing,
  and demonstrated that it significantly reduces long-horizon prediction errors. Moreover,
  when integrated within the MPC framework (HyperMPC), our method consistently outperforms
  existing state-of-the-art techniques.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wegrzynowski25a
month: 0
tex_title: 'Beyond Constant Parameters: Hyper Prediction Models and HyperMPC'
firstpage: 4885
lastpage: 4907
page: 4885-4907
order: 4885
cycles: false
bibtex_author: W\k{e}grzynowski, Jan and Kicki, Piotr and Czechmanowski, Grzegorz
  and Krupka, Maciej Piotr and Walas, Krzysztof
author:
- given: Jan
  family: Węgrzynowski
- given: Piotr
  family: Kicki
- given: Grzegorz
  family: Czechmanowski
- given: Maciej Piotr
  family: Krupka
- given: Krzysztof
  family: Walas
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
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/wegrzynowski25a/wegrzynowski25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
