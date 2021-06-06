---
title: Multiparty Session Types for Safe Runtime Adaptation in an Actor Language
publication_types:
  - "1"
authors:
  - Paul Harvey
  - Simon Fowler
  - Ornela Dardha
  - Simon J. Gay
author_notes: []
publication: 35th European Conference on Object-Oriented Programming 2021
publication_short: ECOOP
abstract: >-
  Human fallibility, unpredictable operational environments, and the
  heterogeneity of hardware devices are driving in the need for software to be
  able to adapt as seen in the Internet of Things or national telecommunication
  networks. Unfortunately, mainstream programming languages do not readily allow
  a software component to sense and respond to its operating environment, by
  discovering, replacing, and communicating with other software components that
  are not part of the original system design, while maintaining static
  correctness guarantees. In particular, if a new component is discovered at
  runtime, there is no guarantee that its communication behaviour is compatible
  with existing components.


  We address this problem by using multiparty session types with explicit connection actions, a type formalism used to model distributed communication protocols. By associating session types with software components, the discovery process can check protocol compatibility and, when required, correctly replace components.


  We present the design and implementation of EnsembleS, the first actor-based language with adaptive features and a static session type system. We apply it to a case study based on an adaptive DNS server. Finally, we formalise the type system of EnsembleS and prove the safety of well-typed programs, making essential use of recent advances in non-classical multiparty session types.
draft: false
featured: false
tags:
  - Actor
  - adaptation
  - sessiontype
  - language
  - trust
  - ""
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-06-06T03:14:36.456Z
---
