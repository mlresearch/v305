---
title: 'Belief-Conditioned One-Step Diffusion: Real-Time Trajectory Planning with
  Just-Enough Sensing'
section: Oral
openreview: t2asRJv2SD
abstract: 'Robots equipped with rich sensor suites can localize reliably in partially-observable
  environments—but powering every sensor continuously is wasteful and often infeasible.
  Belief-space planners address this by propagating pose-belief covariance through
  analytic models and switching sensors heuristically–a brittle, runtime expensive
  approach. Data-driven approaches–including diffusion models–learn multi-modal trajectories
  from demonstrations, but presuppose an accurate, always-on state estimate. We address
  the largely open problem: for a given task in a  mapped environment, which *minimal
  sensor subset* must be active at each location to maintain state uncertainty *just
  low enough* to complete the task? Our key insight is that when a diffusion planner
  is explicitly conditioned on a pose-belief raster and a sensor mask, the spread
  of its denoising trajectories yields a calibrated, differentiable proxy for the
  expected localization error. Building on this insight, we present Belief-Conditioned
  One-Step Diffusion (B-COD), the first planner that, in a 10 ms forward pass, returns
  a short-horizon trajectory, per-waypoint aleatoric variances, and a proxy for localization
  error–eliminating external covariance rollouts. We show that this single proxy suffices
  for a soft-actor–critic to choose sensors online, optimising energy while bounding
  pose-covariance growth. We deploy B-COD in real-time marine trials on an unmanned
  surface vehicle and show that it reduces sensing energy consumption while matching
  the goal-reach performance of an always-on baseline.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: puthumanaillam25a
month: 0
tex_title: 'Belief-Conditioned One-Step Diffusion: Real-Time Trajectory Planning with
  Just-Enough Sensing'
firstpage: 68
lastpage: 92
page: 68-92
order: 68
cycles: false
bibtex_author: Puthumanaillam, Gokul and Penumarti, Aditya and Vora, Manav and Padrao,
  Paulo and Fuentes, Jose and Bobadilla, Leonardo and Shin, Jane and Ornik, Melkior
author:
- given: Gokul
  family: Puthumanaillam
- given: Aditya
  family: Penumarti
- given: Manav
  family: Vora
- given: Paulo
  family: Padrao
- given: Jose
  family: Fuentes
- given: Leonardo
  family: Bobadilla
- given: Jane
  family: Shin
- given: Melkior
  family: Ornik
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
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/puthumanaillam25a/puthumanaillam25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
