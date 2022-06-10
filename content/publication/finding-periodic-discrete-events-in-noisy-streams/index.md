---
title: Finding Periodic Discrete Events in Noisy Streams
publication_types:
  - "1"
authors:
  - Abhirup Ghosh
  - Christopher Lucas
  - Rik Sarkar
doi: https://dl.acm.org/doi/abs/10.1145/3132847.3132981
publication: Conference on Information and Knowledge Management
publication_short: CIKM
abstract: Periodic phenomena are ubiquitous, but detecting and predicting
  periodic events can be difficult in noisy environments. We describe a model of
  periodic events that covers both idealized and realistic scenarios
  characterized by multiple kinds of noise. The model incorporates
  false-positive events and the possibility that the underlying period and phase
  of the events change over time. We then describe a particle filter that can
  efficiently and accurately estimate the parameters of the process generating
  periodic events intermingled with independent noise events. The system has a
  small memory footprint, and, unlike alternative methods, its computational
  complexity is constant in the number of events that have been observed. As a
  result, it can be applied in low-resource settings that require real-time
  performance over long periods of time. In experiments on real and simulated
  data we find that it outperforms existing methods in accuracy and can track
  changes in periodicity and other characteristics in dynamic event streams.
draft: false
featured: true
tags:
  - Temporal
  - ParticleFilter
slides: cikm2017.pptx
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Particle filter-based periodicity detection method for signals with
  drifting phase, changing periodicity, and false-positive events.
date: 2017-11-06T11:23:44.150Z
---
