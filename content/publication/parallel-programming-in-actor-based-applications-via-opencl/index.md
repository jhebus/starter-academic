---
title: "Parallel Programming in Actor-Based Applications via OpenCL "
publication_types:
  - "1"
authors:
  - Paul Harvey
  - K. Hentschel
  - Joseph Sventek
doi: https://doi.org/10.1145/2814576.2814732
publication: Proceedings of the 16th Annual Middleware Conference
publication_short: MIddleware
abstract: >-
  GPU and multicore hardware architectures are commonly used in many different
  application areas to accelerate problem solutions relative to single CPU
  architectures. The typical approach to accessing these hardware architectures
  requires embedding logic into the programming language used to construct the
  application; the two primary forms of embedding are: calls to API routines to
  access the concurrent functionality, or pragmas providing concurrency hints to
  a language compiler such that particular blocks of code are targeted to the
  concurrent functionality. The former approach is verbose and semantically
  bankrupt, while the success of the latter approach is restricted to simple,
  static uses of the functionality.


  This paper presents an extension to an existing actor-based programming model and runtime to support executing applications on parallel hardware architectures. Besides the glove-like fit of a kernel to the actor abstraction, quantitative code analysis shows that actor-based kernels are always significantly simpler than API-based coding, and generally simpler than pragma-based coding. The structuring of applications in this manner, enables the runtime to automate the initialisation and interaction with these parallel hardware platforms. Performance measurements show that the overheads of actor-based kernels are commensurate to API-based kernels, and range from equivalent to vastly improved for pragma-based annotations, both for sample and real-world applications.
draft: false
featured: false
categories:
  - actors
  - gpu
  - paralleprogramming
  - language
  - runtime
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2015-11-24T07:53:25.255Z
---
