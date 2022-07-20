---
abstract: >-
  This paper considers the problem of privately reporting counts of events
  recorded by devices in different regions of the plane. Unlike previous range
  query methods, our approach is not limited to rectangular ranges. We devise
  novel hierarchical data structures to answer queries over arbitrary planar
  graphs. This construction relies on balanced planar separators to represent
  shortest paths using O(logn) number of canonical paths, where n is the number
  of nodes in the graph. Pre-computed sums along these canonical paths allow
  efficient computations of 1D counting range queries along any shortest path.
  We make use of differential forms together with the 1D mechanism to answer 2D
  queries in which a range is a union of faces in the planar graph. The methods
  are designed such that the range queries could be answered with differential
  privacy guarantee on any single event, with only a poly-logarithmic error.
  They also allow private range queries to be performed in a distributed setup.
  Theoretical and experimental results confirm that the methods are efficient
  and accurate on real data and incur less error than competing existing
  methods.
slides: ''
url_pdf: 'https://homepages.inf.ed.ac.uk/rsarkar/papers/range-privacy.pdf'
publication_types:
  - '1'
authors:
  - Abhirup Ghosh
  - Jiaxin Ding
  - Rik Sarkar
  - Jie Gao
author_notes:
  - Equal contribution
  - Equal contribution
publication: INFOCOM
summary: >-
  Proposes a private and efficient data structure to answer range queries along
  paths in a planar graph.
url_dataset: ''
url_project: ''
publication_short: ''
url_source: ''
url_video: ''
title: Differentially Private Range Counting in Planar Graphs for Spatial Sensing
doi: 'https://ieeexplore.ieee.org/document/9155480'
featured: true
tags:
  - Spatial-data
  - Statistical-privacy
projects: []
image:
  caption: ''
  focal_point: ''
  preview_only: false
  filename: null
date: 2020-07-06T20:22:19.194Z
url_slides: 'https://coseners.net/wp-content/uploads/2020/07/ghosh2020.pdf'
publishDate: 2020-07-06T00:00:00.000Z
url_poster: ''
url_code: ''
---
