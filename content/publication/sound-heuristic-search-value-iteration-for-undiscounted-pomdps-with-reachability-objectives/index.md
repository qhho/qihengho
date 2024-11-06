---
title: Sound Heuristic Search Value Iteration for Undiscounted POMDPs with
  Reachability Objectives
publication_types:
  - "0"
  - "1"
authors:
  - Qi Heng Ho
  - Martin Feather
  - Federico Rossi
  - Zachary Sunberg
  - Morteza Lahijanian
publication: Uncertainty in Artificial Intelligence
abstract: Partially Observable Markov Decision Processes (POMDPs) are powerful
  models for sequential decision making under transition and observation
  uncertainties. This paper studies the challenging yet important problem in
  POMDPs known as the (indefinite-horizon) Maximal Reachability Probability
  Problem (MRPP), where the goal is to maximize the probability of reaching some
  target states. This is also a core problem in model checking with logical
  specifications and is naturally undiscounted (discount factor is one).
  Inspired by the success of point-based methods developed for discounted
  problems, we study their extensions to MRPP. Specifically, we focus on
  trial-based heuristic search value iteration techniques and present a novel
  algorithm that leverages the strengths of these techniques for efficient
  exploration of the belief space (informed search via value bounds) while
  addressing their drawbacks in handling loops for indefinite-horizon problems.
  The algorithm produces policies with two-sided bounds on optimal reachability
  probabilities. We prove convergence to an optimal policy from below under
  certain conditions. Experimental evaluations on a suite of benchmarks show
  that our algorithm outperforms existing methods in almost all cases in both
  probability guarantees and computation time.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-11-06T03:01:23.517Z
---
