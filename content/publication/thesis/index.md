---
title: A linguistic approach to concurrent, distributed, and adaptive
  programming across heterogeneous platforms
publication_types:
  - "7"
authors:
  - Paul Harvey
doi: http://theses.gla.ac.uk/id/eprint/6749
abstract: >-
  Two major trends in computing hardware during the last decade have been an
  increase in the number of processing cores found in individual computer
  hardware platforms and an ubiquity of distributed, heterogeneous systems.
  Together, these changes can improve not only the performance of a range of
  applications, but the types of applications that can be created.


  Despite the advances in hardware technology, advances in programming of such systems has not kept pace. Traditional concurrent programming has always been challenging, and is only set to be come more so as the level of hardware concurrency increases. The different hardware platforms which make up heterogeneous systems come with domain-specific programming models, which are not designed to interact, or take into account the different resource-constraints present across different hardware devices, motivating a need for runtime reconfiguration or adaptation.


  This dissertation investigates the actor model of computation as an appropriate abstraction to address the issues present in programming concurrent, distributed, and adaptive applications across different scales and types of computing hardware. Given the limitations of other approaches, this dissertation describes a new actor-based programming language (Ensemble) and its runtime to address these challenges. The goal of this language is to enable non-specialist programmers to take advantage of parallel, distributed, and adaptive programming without the programmer requiring in-depth knowledge of hardware architectures or software frameworks. There is also a description of the design and implementation of the runtime system which executes Ensemble applications across a range of heterogeneous platforms.


  To show the suitability of the actor-based abstraction in creating applications for such systems, the language and runtime were evaluated in terms of linguistic complexity and performance. These evaluations covered programming embedded, concurrent, distributed, and adaptable applications, as well as combinations thereof. The results show that the actor provides an objectively simple way to program such systems without sacrificing performance.
draft: false
featured: false
tags:
  - ensemble
  - adaptive
  - runtime
  - OS
  - inceOS
  - ensembleVM
  - GPU
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2015-07-01T13:38:32.816Z
---
