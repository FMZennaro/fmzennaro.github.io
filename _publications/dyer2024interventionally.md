---
title: "Interventionally Consistent Surrogates for Agent-based Simulators"
authors: "Joel Dyer, Nicholas Bishop, Yorgos Felekis, Fabio Massimo Zennaro, Anisoara Calinescu, Theodoros Damoulas, Michael Wooldridge"
collection: publications
permalink: /publication/dyer2024interventionally
date: 2024-10-24
venue: 'NeurIPS 2024 (Conference on Neural Information Processing Systems)'
paperurl: 'https://arxiv.org/abs/2312.11158'
---

Agent-based simulators provide granular representations of complex intelligent systems by directly modelling the interactions of the system's constituent agents. Their high-fidelity nature enables hyper-local policy evaluation and testing of what-if scenarios, but is associated with large computational costs that inhibits their widespread use. Surrogate models can address these computational limitations, but they must behave consistently with the agent-based model under policy interventions of interest. In this paper, we capitalise on recent developments on causal abstractions to develop a framework for learning interventionally consistent surrogate models for agent-based simulators. Our proposed approach facilitates rapid experimentation with policy interventions in complex systems, while inducing surrogates to behave consistently with high probability with respect to the agent-based simulator across interventions of interest. We demonstrate with empirical studies that observationally trained surrogates can misjudge the effect of interventions and misguide policymakers towards suboptimal policies, while surrogates trained for interventional consistency with our proposed method closely mimic the behaviour of an agent-based model under interventions of interest.
