---
title: Feasibility-Guided Safety-Aware Model Predictive Control for Jump Markov
  Linear Systems
publication_types:
  - "1"
authors:
  - Zakariya Laouar
  - Qi Heng Ho
  - Rayan Mazouz
  - Tyler Becker
  - and Zachary Sunberg
publication: IEEE/RSJ International Conference on Intelligent Robots and Systems
publication_short: IROS
abstract: In this paper, we present a controller framework that synthesizes
  control policies for Jump Markov Linear Systems subject to stochastic mode
  switches and imperfect mode estimation. Our approach builds on safe and robust
  methods for Model Predictive Control (MPC), but in contrast to existing
  approaches that either optimize without regard to feasibility or utilize soft
  constraints that increase computational requirements, we employ a safe and
  robust control approach informed by the feasibility of the optimization
  problem. We formulate and encode finite horizon safety for multiple model
  systems in our MPC design using Control Barrier Functions (CBFs). When subject
  to inaccurate hybrid state estimation, our feasibility-guided MPC generates a
  control policy that is maximally robust to uncertainty in the system's modes.
  We evaluate our approach on an orbital rendezvous problem and a six
  degree-of-freedom hexacopter under several scenarios and benchmarks to
  demonstrate the utility of the framework. Results indicate that the proposed
  technique of maximizing the robustness horizon, and the use of CBFs for safety
  awareness, improve the overall safety and performance of MPC for Jump Markov
  Linear Systems.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-11-13T21:36:08.927Z
---