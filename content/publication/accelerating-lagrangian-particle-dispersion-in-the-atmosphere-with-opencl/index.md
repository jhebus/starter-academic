---
title: Accelerating Lagrangian Particle Dispersion in the Atmosphere with OpenCL
publication_types:
  - "1"
authors:
  - "*Paul Harvey*"
  - _Saji_ Hameed
  - Wim Vanderbauhede
author_notes: []
doi: https://doi.org/10.1145/2664666.2664672
publication: Proceedings of the First International Workshop on OpenCL
publication_short: IWOCL
abstract: >-
  FLEXPART is a popular simulator that models the transport and diffusion of air
  pollutants, based on the Lagrangian approach. It is capable of regional and
  global simulation and supports both forward and backward runs. A complex model
  like this contains many calculations suitable for parallelisation. Recently, a
  GPU-accelerated version of the simulator (FLEXCPP) has been written in
  C++/CUDA. As CUDA is only supported on NVIDIA GPUs, such an implementation is
  tied to a single hardware vendor, and is not able to take advantage of other
  hardware acceleration platforms.


  This paper presents an OpenCL/C++ version of FLEXCPP, called FlexOcl. This simulator provides all the functionality of FLEXCPP, and has been extended to include modelling of the decay of radioactive particles. A performance comparison between the two simulators has been performed on GPU, and the performance of FlexOcl has also been evaluated on the Intel Xeon Phi, as well as a number of other hardware platforms. Our results show that the OpenCL code performs better than CUDA code on GPUs, and that equivalent performance is seen on the Xeon Phi for this type of application.
draft: false
featured: false
tags:
  - OpenCL
  - FLEXPART
  - weather simulation
  - GPU
  - multicore
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2014-05-04T14:13:26.653Z
---
