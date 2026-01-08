---
title: "Using causal abstractions to accelerate decision-making in complex bandit problems"
authors: "Joel Dyer, Nicholas Bishop, Anisoara Calinescu, Michael Wooldridge, Fabio Massimo Zennaro"
collection: publications
permalink: /publication/dyer2025using
date: 2025-12-06
venue: 'NeurIPS 2025 Workshop on Uncovering Causality in Science'
paperurl: 'https://arxiv.org/abs/2509.04296'
---

Although real-world decision-making problems can often be encoded as causal multi-armed bandits (CMABs) at different levels of abstraction, a general methodology exploiting the information and computational advantages of each abstraction level is missing. In this paper, we propose AT-UCB, an algorithm which efficiently exploits shared information between CMAB problem instances defined at different levels of abstraction. More specifically, AT-UCB leverages causal abstraction (CA) theory to explore within a cheap-to-simulate and coarse-grained CMAB instance, before employing the traditional upper confidence bound (UCB) algorithm on a restricted set of potentially optimal actions in the CMAB of interest, leading to significant reductions in cumulative regret when compared to the classical UCB algorithm. We illustrate the advantages of AT-UCB theoretically, through a novel upper bound on the cumulative regret, and empirically, by applying AT-UCB to epidemiological simulators with varying resolution and computational cost.
