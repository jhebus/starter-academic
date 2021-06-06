---
title: "Scission: Performance-driven and Context-aware Cloud-Edge Distribution
  of Deep Neural Networks"
publication_types:
  - "1"
authors:
  - Luke Lockheart
  - Paul Harvey
  - Pierre Imai
  - Peter Willis
  - Blesson Varghese
doi: 10.1109/UCC48980.2020.00044
publication: " 2020 IEEE/ACM 13th International Conference on Utility and Cloud Computing"
publication_short: UCC
abstract: >-
  Partitioning and distributing deep neural networks (DNNs) across end-devices,
  edge resources and the cloud has a potential twofold advantage: preserving
  privacy of the input data, and reducing the ingress bandwidth demand beyond
  the edge. However, for a given DNN, identifying the optimal partition
  configuration for distributing the DNN that maximizes performance is a
  significant challenge. This is because the combination of potential target
  hardware resources that maximizes performance and the sequence of layers of
  the DNN that should be distributed across the target resources needs to be
  determined, while accounting for user-defined objectives/constraints for
  partitioning. 


  This paper presents Scission, a tool for automated benchmarking of DNNs on a given set of target device, edge and cloud resources for determining optimal partitions that maximize DNN performance. The decision-making approach is context-aware by capitalizing on hardware capabilities of the target resources, their locality, the characteristics of DNN layers, and the network condition. Experimental studies are carried out on 18 DNNs. The decisions made by Scission cannot be manually made by a human given the complexity and the number of dimensions affecting the search space. The benchmarking overheads of Scission allow for responding to operational changes periodically rather than in real-time. Scission is available for public download 1 .
draft: false
featured: false
tags:
  - edgecomputing
  - DNN
  - partitioning
  - benchmark
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-12-07T03:52:57.826Z
---
