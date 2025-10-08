---
title: Steering Your Diffusion Policy with Latent Space Reinforcement Learning
section: Oral
openreview: jU7AbGq3se
abstract: 'Robotic control policies learned from human demonstrations have achieved
  impressive results in many real-world applications. However, in scenarios where
  initial performance is not satisfactory, as is often the case in novel open-world
  settings, such behavioral cloning (BC)-learned policies typically require collecting
  additional human demonstrations to further improve their behavior—an expensive and
  time-consuming process. In contrast, reinforcement learning (RL) holds the promise
  of enabling autonomous online policy improvement, but often falls short of achieving
  this due to the large number of samples it typically requires. In this work we take
  steps towards enabling fast autonomous adaptation of BC-trained policies via efficient
  real-world RL. Focusing in particular on diffusion policies—a state-of-the-art BC
  methodology—we propose *diffusion steering via reinforcement learning* (DSRL): adapting
  the BC policy by running RL over its latent-noise space. We show that DSRL is highly
  sample efficient, requires only black-box access to the BC policy, and enables effective
  real-world autonomous policy improvement. Furthermore, DSRL avoids many of the challenges
  associated with finetuning diffusion policies, obviating the need to modify the
  weights of the base policy at all. We demonstrate DSRL on simulated benchmarks,
  real-world robotic tasks, and for adapting pretrained generalist policies, illustrating
  its sample efficiency and effective performance at real-world policy improvement.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wagenmaker25a
month: 0
tex_title: Steering Your Diffusion Policy with Latent Space Reinforcement Learning
firstpage: 258
lastpage: 282
page: 258-282
order: 258
cycles: false
bibtex_author: Wagenmaker, Andrew and Zhang, Yunchu and Nakamoto, Mitsuhiko and Park,
  Seohong and Yagoub, Waleed and Nagabandi, Anusha and Gupta, Abhishek and Levine,
  Sergey
author:
- given: Andrew
  family: Wagenmaker
- given: Yunchu
  family: Zhang
- given: Mitsuhiko
  family: Nakamoto
- given: Seohong
  family: Park
- given: Waleed
  family: Yagoub
- given: Anusha
  family: Nagabandi
- given: Abhishek
  family: Gupta
- given: Sergey
  family: Levine
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
pdf: https://raw.githubusercontent.com/mlresearch/v305/main/assets/wagenmaker25a/wagenmaker25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
