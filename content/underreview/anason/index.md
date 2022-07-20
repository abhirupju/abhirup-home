---
title: >-
  In-Network Approximate and Efficient Spatiotemporal Range Queries on Moving
  Objects
publication_types:
  - '3'
authors:
  - Guang Yang
  - Abhirup Ghosh
  - Thomas Heinis
abstract: >-
  A spatiotemporal range count query on the moving objects asks for the count of
  objects in a given spatial region and a time interval. In this paper, we study
  an in-network query system, where a set of static movement sensors answer
  queries collaboratively at query time without aggregating the data at a
  central place.

  The two main challenges for efficient in-network processing are (1) as setting
  up and maintaining a sensing infrastructure is costly, how to decide their
  placements. (2) as the sensors typically are limited in computational power,
  storage, communication bandwidth, and energy, how to enable real-time query
  response with the resource constraints.

  We develop a framework using in-network approximate query processing. The
  framework is grounded on discrete differential forms and enables queries on
  irregular spatial ranges. When the query distribution is known a priori, we
  propose a submodular maximization-based method to choose a subset of the
  domain to sense. When the query distribution is unknown or dynamic, we
  evaluate various sampling methods to select the regions to sense. We use
  constant-sized regression models to represent the sensing events at each
  sensor to answer queries on arbitrary temporal ranges without storing the
  entire history of the tracking events. This significantly reduces the storage
  and processing time in each sensing device. The final approximation comes from
  both spatial (subsampling the domain) and temporal (regression models)
  dimensions.

  Our exhaustive empirical evaluation on a real-world mobility dataset shows at
  most a relative error of 13.8\(\percent\) while using 25.6\(\percent\) of
  sensors. Furthermore, we achieve a speedup of 3.5X and a storage reduction of
  99.96\(\percent\) compared to finding the exact count.
draft: false
featured: true
tags:
  - Topology
  - Spatial Graph
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Releasing differentially private ML models for data streams.
date: '2022-07-08sT00:18:26.212Z'
---
