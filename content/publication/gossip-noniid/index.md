---
title: >-
  Modeling with Homophily Driven Heterogeneous Data in Gossip Learning
publication_types:
  - '3'
authors:
  - Abhirup Ghosh
  - Cecilia Mascolo
doi: awaiting
publication: International Joint Conference on Artificial Intelligence
publication_short: IJCAI
abstract: >-
  Training deep learning models on data distributed and kept local on edge
  devices such as mobile phones is a prominent recent research direction. In a
  gossip learning system, each participating device maintains a model trained on
  its local data and iteratively aggregates with the models from its neighbours
  in a communication network. While the fully distributed operation comes with
  natural advantages over the centralized orchestration in federated learning,
  its convergence rate becomes particularly slow when the data distribution is
  heterogeneous and aligns with the clustered structure of the communication
  network. These characteristics are pervasive across practical applications as
  people with similar interests (thus producing similar data) tend to create
  communities. In this regard, here we make two important contributions. First,
  we propose a data-driven softmax distribution based neighbor weighting
  strategy for aggregating the models to enable faster diffusion of knowledge
  across the communities in the network that leads to quicker convergence. The
  strategy is flexible and is extended to make it computationally efficient and
  fair in the sense that the devices quickly converge to the same model.
  Secondly, we propose a novel way to distribute the data over a communication
  network. We also build a bird image classification dataset with a
  communication network. We believe these can address the need for datasets for
  gossip learning. Our exhaustive empirical evaluations using multiple synthetic
  and real-world datasets verify that our proposed method attains a faster
  convergence rate than the baselines including federated learning.
draft: false
featured: true
tags:
  - Gossip-learning
  - Deep-learning
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: >-
  Proposes how to handle label skew in decentralized learning where the users
  connect peer to peer.
date: '2023-08-22'
---
