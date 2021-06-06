---
title: "WattsApp: Power-Aware Container Scheduling"
publication_types:
  - "1"
authors:
  - Hemant Mehta
  - Paul Harvey
  - Omer Rana
  - Rajkumar Buyya
  - Blesson Varghese
doi: 10.1109/UCC48980.2020.00027
publication: "2020 IEEE/ACM 13th International Conference on Utility and Cloud Computing "
publication_short: UCC
abstract: Containers are popular for deploying workloads. However, there are
  limited software-based methods (hardware- based methods are expensive) for
  obtaining the power consumed by containers to facilitate power-aware container
  scheduling. This paper presents WattsApp, a tool underpinned by a six step
  software-based method for power-aware container scheduling to minimize power
  cap violations on a server. The proposed method relies on a neural
  network-based power estimation model and a power capped container scheduling
  technique. Experimental studies are pursued in a lab-based environment on 10
  benchmarks on Intel and ARM processors. The results highlight that power
  estimation has negligible overheads - nearly 90% of all data samples can be
  estimated with less than a 10% error, and the Mean Absolute Percentage Error
  (MAPE) is less than 6%. The power-aware scheduling of WattsApp is more
  effective than Intel's Running Power Average Limit (RAPL) based power capping
  as it does not degrade the performance of all running containers.
draft: false
featured: false
tags:
  - container scheduling
  - workload deployment
  - power-aware scheduling
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-12-07T04:05:34.141Z
---
