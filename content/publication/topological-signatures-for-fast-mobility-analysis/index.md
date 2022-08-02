---
url_video: 'https://www.youtube.com/embed/OACxnEA4Wls'
title: Topological Signatures For Fast Mobility Analysis
publication_types:
  - '1'
authors:
  - Abhirup Ghosh
  - Benedek Rozemberczki
  - Subramanian Ramamoorthy
  - Rik Sarkar
doi: 'https://dl.acm.org/doi/abs/10.1145/3274895.3274952'
publication: >-
  Proceedings of the 26th ACM SIGSPATIAL International Conference on Advances in
  Geographic Information Systems
publication_short: SigSpatial
abstract: >-
  Analytic methods can be difficult to build and costly to train for mobility
  data. We show that information about the topology of the space and how mobile
  objects navigate the obstacles can be used to extract insights about mobility
  at larger distance scales. The main contribution of this paper is a
  topological signature that maps each trajectory to a relatively low
  dimensional Euclidean space, so that now they are amenable to standard
  analytic techniques. Data mining tasks: nearest neighbor search with locality
  sensitive hashing, clustering, regression, etc., work more efficiently in this
  signature space. We define the problem of mobility prediction at different
  distance scales, and show that with the signatures simple k nearest neighbor
  based regression performs an accurate prediction. Experiments on multiple real
  datasets show that the framework using topological signatures is accurate on
  all tasks, and substantially more efficient than machine learning applied to
  raw data. Theoretical results show that the signatures contain enough
  topological information to reconstruct non-self-intersecting trajectories upto
  homotopy type. The construction of signatures is based on a differential form
  that can be generated in a distributed setting using local communication, and
  a signature can be locally and inexpensively updated and communicated by a
  mobile agent.
draft: false
featured: false
tags:
  - Mobility
  - Topology
image:
  filename: ''
  focal_point: Smart
  preview_only: false
summary: >-
  An efficient framework to map GPS trajectories to Euclidean vectors using
  differential topology. This enables Euclidean machine learning tools for the
  trajectories.
date: 2018-11-06T08:43:59.668Z
---
