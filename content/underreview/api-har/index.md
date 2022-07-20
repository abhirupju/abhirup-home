---
title: >-
  Investigating Domain agnostic Performance in Activity Recognition using
  Accelerometer Data (Workshop)
publication_types:
  - '3'
authors:
  - Api Hasthanasombat
  - Abhirup Ghosh
  - Cecilia Mascolo
abstract: >-
  Human activity recognition (HAR) models suffer significant performance
  degradation when faced with data heterogeneity (device, users, environments)
  at test time. Current approaches to this problem using domain adaptation or
  transfer learning attempt to improve performance in one specific target
  domain, often using data from that domain. Requiring access to data from the
  target domain is limiting and cannot be generally assumed. In addition, there
  is often no single target domain, but rather multiple ones arising from
  different sources of data heterogeneity. One way to achieve good performance
  in this setting would be to gather data from all potential domains the model
  may encounter at deployment  this is generally infeasible.

  This work presents the case for training models which are domain agnostic,
  i.e., that generalise to unseen test domains. This requires a new way to
  evaluate models; we discuss a regime called leave-datasets-out, and present a
  benchmark for the task of HAR. Two state-of-the-art deep models in the
  literature are tested; they significantly under-perform in unseen domains when
  compared to their performance on seen domains. It is shown that under this new
  evaluation regime, a simple model with an appropriate inductive bias performs
  at least as well as two current deep models on the benchmark, with a p-value
  in the order of 0.0005 and 0.13 when testing for a difference in mean
  accuracy, whilst being at least 10 times faster to train.
draft: false
featured: true
tags:
  - HAR
  - Deep-learning
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Generalizability of HAR models to unseen data distribution.
date: '2022-07-08sT00:18:26.212Z'
---
