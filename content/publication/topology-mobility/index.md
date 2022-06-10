---
abstract: Analytic methods can be difficult to build and costly to train for mobility data. We show that information about the topology of the space and how mobile objects navigate the obstacles can be used to extract insights about mobility at larger distance scales. The main contribution of this paper is a topological signature that maps each trajectory to a relatively low dimensional Euclidean space, so that now they are amenable to standard analytic techniques. Data mining tasks: nearest neighbor search with locality sensitive hashing, clustering, regression, etc., work more efficiently in this signature space. We define the problem of mobility prediction at different distance scales, and show that with the signatures simple k nearest neighbor based regression perform accurate prediction. Experiments on multiple real datasets show that the framework using topological signatures is accurate on all tasks, and substantially more efficient than machine learning applied to raw data. Theoretical results show that the signatures contain enough topological information to reconstruct non-self-intersecting trajectories upto homotopy type. The construction of signatures is based on a differential form that can be generated in a distributed setting using local communication, and a signature can be locally and inexpensively updated and communicated by a mobile agent.
slides: ""
url_pdf: https://homepages.inf.ed.ac.uk/rsarkar/papers/range-privacy.pdf
publication_types:
  - "1"
authors:
  - Abhirup Ghosh
  - Benedek Rozemberczki
  - Subramanian Ramamoorthy
  - Rik Sarkar
author_notes:
publication: SigSpatial
summary: An efficient framework to map trajectories to Euclidean vectors called signatures using differential topology. This enables Euclidean machine learning tools for the trajectories.
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Topological Signatures For Fast Mobility Analysis
doi: https://dl.acm.org/doi/abs/10.1145/3274895.3274952
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: null
date: 2018-11-06T00:00:000.000Z
url_slides: https://coseners.net/wp-content/uploads/2020/07/ghosh2020.pdf
publishDate: 2018-11-06T00:00:000.000Z
url_poster: ""
url_code: ""
---
