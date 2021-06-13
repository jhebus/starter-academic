---
title: "Wireless Sensor Network Simulation With Xen "
publication_types:
  - "1"
authors:
  - Paul Harvey
  - Joseph Sventek
doi: https://dl.acm.org/doi/abs/10.5555/2499604.2499608
publication: Proceedings of the 46th Annual Simulation Symposium
publication_short: ANSS 13
abstract: The large-scale and inaccessibility of deployed wireless sensor
  networks mandate that the code installed in sensor nodes be rigorously tested
  prior to deployment. Such testing is primarily done using software simulators.
  Discrete event simulators, by their very nature, mask race conditions in the
  code since simulated interrupts never interrupt running code; an additional
  limitation of most such simulators is that all simulated nodes execute the
  same application code, at variance with common practice in actual deployments.
  Java-based simulators often suffer from efficiency issues, which limits the
  scale and performance of the simulation. Since all of these problems reduce
  confidence in the deployed system, the focus of this work is to eliminate
  these problems via complete emulation of wireless sensor networks using
  virtualisation techniques in a scalable manner. This work describes the
  virtualisation of the Contiki, TinyOS, and InceOS wireless sensor network
  operating systems to execute as guest domains over the Xen hypervisor. In each
  case, the hardware virtualisation is performed at the lowest possible layer,
  maximising the amount of OS and application code which is executed during the
  emulation. This work also introduces a novel Xen-specific radio model
  mechanism, easing the introduction of different radio models for use during
  emulations.
draft: false
featured: false
tags:
  - Xen
  - wireless sensor network
  - TinyOS
  - Contiki
  - InceOS
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2013-04-01T02:09:41.265Z
---
