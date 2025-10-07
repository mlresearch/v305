---
title: 'HALO : Human Preference Aligned Offline Reward Learning for Robot Navigation'
section: Poster
openreview: PMKwnV6Azi
abstract: 'In this paper, we introduce HALO, a novel Offline Reward Learning algorithm
  that quantifies human intuition in navigation into a vision-based reward function
  for robot navigation. HALO learns a reward model from offline data, leveraging expert
  trajectories collected from mobile robots. During training, actions are randomly
  sampled from the action space around the expert action and ranked using a Boltzmann
  probability distribution that combines their distance to the expert action with
  human preference scores derived from intuitive navigation queries based on the corresponding
  egocentric camera feed. These scores establish preference rankings, enabling the
  training of a novel reward model based on Plackett-Luce loss, which allows for preference-driven
  navigation. To demonstrate the effectiveness of HALO, we deploy its reward model
  in two downstream applications: (i) an offline learned policy trained directly on
  the HALO-derived rewards, and (ii) a model-predictive-control (MPC) based planner
  that incorporates the HALO reward as an additional cost term. This showcases the
  versatility of HALO across both learning-based and classical navigation frameworks.
  Our real-world deployments on a Clearpath Husky across multiple scenarios demonstrate
  that policies trained with HALO achieve improved performance over state-of-the-art
  methods in terms of success rate and normalized trajectory length while maintaining
  lower Fréchet distance with the human expert trajectories.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: seneviratne25a
month: 0
tex_title: 'HALO : Human Preference Aligned Offline Reward Learning for Robot Navigation'
firstpage: 3267
lastpage: 3284
page: 3267-3284
order: 3267
cycles: false
bibtex_author: Seneviratne, Gershom and An, Jianyu and Ellahy, Sahire and Weerakoon,
  Kasun and Elnoor, Mohamed Bashir and Kannan, Jonathan Deepak and Sunil, Amogha Thalihalla
  and Manocha, Dinesh
author:
- given: Gershom
  family: Seneviratne
- given: Jianyu
  family: An
- given: Sahire
  family: Ellahy
- given: Kasun
  family: Weerakoon
- given: Mohamed Bashir
  family: Elnoor
- given: Jonathan Deepak
  family: Kannan
- given: Amogha Thalihalla
  family: Sunil
- given: Dinesh
  family: Manocha
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
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/seneviratne25a/seneviratne25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
