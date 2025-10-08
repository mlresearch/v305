---
title: Learning Long-Context Diffusion Policies via Past-Token Prediction
section: Poster
openreview: o0LBjJxUeS
abstract: 'Reasoning over long sequences of observations and actions is essential
  for many robotic tasks.  Yet, learning effective long-context policies from demonstrations
  remains challenging.  As context length increases, training becomes increasingly
  expensive due to rising memory demands, and policy performance often degrades as
  a result of spurious correlations. Recent methods typically sidestep these issues
  by truncating context length, discarding historical information that may be critical
  for subsequent decisions. In this paper, we propose an alternative approach that
  explicitly regularizes the retention of past information. We first revisit the copycat
  problem in imitation learning and identify an opposite challenge in recent diffusion
  policies: rather than over-relying on prior actions, they often fail to capture
  essential dependencies between past and future actions. To address this, we introduce
  Past-Token Prediction (PTP), an auxiliary task in which the policy learns to predict
  past action tokens alongside future ones. This regularization significantly improves
  temporal modeling in the policy head, with minimal reliance on visual representations.
  Building on this observation, we further introduce a multistage training strategy:
  pre-train the visual encoder with short contexts, and fine-tune the policy head
  using cached long-context embeddings.  This strategy preserves the benefits of PTP
  while greatly reducing memory and computational overhead. Finally, we extend PTP
  into a self-verification mechanism at test time, enabling the policy to score and
  select candidates consistent with past actions during inference. Experiments across
  four real-world and six simulated tasks demonstrate that our proposed method improves
  the performance of long-context diffusion policies by 3$\times$ and accelerates
  policy training by more than 10$\times$. Videos are available at https://ptp-robot.github.io.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: villasevil25a
month: 0
tex_title: Learning Long-Context Diffusion Policies via Past-Token Prediction
firstpage: 1744
lastpage: 1755
page: 1744-1755
order: 1744
cycles: false
bibtex_author: Villasevil, Marcel Torne and Tang, Andy and Liu, Yuejiang and Finn,
  Chelsea
author:
- given: Marcel Torne
  family: Villasevil
- given: Andy
  family: Tang
- given: Yuejiang
  family: Liu
- given: Chelsea
  family: Finn
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
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/villasevil25a/villasevil25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
