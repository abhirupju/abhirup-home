---
title: Less Data Can Be Better for Domain Generalization
publication_types:
  - '3'
authors:
  - Api Hasthanasombat
  - Abhirup Ghosh
  - Cecilia Mascolo
abstract: >-
  Classical machine learning models face significant performance degradation
  when tested on unseen test domains. Solutions in domain generalization aim to
  solve this problem without access to data from the test distribution during
  training, by increasing training data diversity or introducing certain
  inductive biases into the training procedure. In either case, there is a
  general consensus that more data is better for performance. We show that more
  data does not always imply better performance on unseen domains. In this paper
  we propose a data filtering method, using ideas from causality, to select a
  subset of the training data to improve generalization and data efficiency
  simultaneously. We find empirical evidence using both synthetic and real world
  tabular datasets for regression problems. Using only 10\(\percent\) of the
  dataset in training the method achieves a similar error in unseen test
  distributions compared to when trained using the full dataset. This result
  provides evidence to the counter-intuitive idea that in certain scenarios,
  more data can be detrimental to out-of-distribution performance, whilst a
  selected subset can in fact improve such performance. This result raises
  questions which can help us better understand the problem of domain
  generalization.
draft: false
featured: false
tags:
  - Model-generalization
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: null
date: '2022-07-08sT00:18:26.212Z'
---
