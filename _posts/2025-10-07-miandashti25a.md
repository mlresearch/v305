---
title: Uncertainty-Aware Scene Understanding via Efficient Sampling-Free Confidence
  Estimation
section: Poster
openreview: Cv3ihZYkZf
abstract: Reliable scene understanding requires not only accurate predictions but
  also well-calibrated confidence estimates to ensure calibrated uncertainty estimation,
  especially in safety-critical domains like autonomous driving. In this context,
  semantic segmentation of LiDAR points supports real-time 3D scene understanding,
  where reliable uncertainty estimates help identify potentially erroneous predictions.
  While most existing calibration approaches focus on modeling epistemic uncertainty,
  they often overlook aleatoric uncertainty arising from measurement inaccuracies,
  which is especially prevalent in LiDAR data and essential for real-world deployment.
  In this work, we introduce a sampling-free approach for estimating well-calibrated
  confidence values by explicitly modeling aleatoric uncertainty in semantic segmentation,
  achieving alignment with true classification accuracy and reducing inference time
  compared to sampling-based methods. Evaluated on the real-world SemanticKITTI benchmark,
  our approach achieves 1.70% and 1.33% Adaptive Calibration Error (ACE) in semantic
  segmentation of LiDAR data using RangeViT and SalsaNext models, and is more than
  one order of magnitude faster than the comparable baseline. Furthermore, reliability
  diagrams reveal that our method produces underconfident rather than overconfident
  predictions — an advantageous property in safety-critical systems.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: miandashti25a
month: 0
tex_title: Uncertainty-Aware Scene Understanding via Efficient Sampling-Free Confidence
  Estimation
firstpage: 4401
lastpage: 4417
page: 4401-4417
order: 4401
cycles: false
bibtex_author: Miandashti, Hanieh Shojaei and Zou, Qianqian and Brenner, Claus
author:
- given: Hanieh Shojaei
  family: Miandashti
- given: Qianqian
  family: Zou
- given: Claus
  family: Brenner
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
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/miandashti25a/miandashti25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
