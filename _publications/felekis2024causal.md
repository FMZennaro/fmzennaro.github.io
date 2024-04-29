---
title: "Causal Optimal Transport of Abstractions"
authors: "Yorgos Felekis, Fabio Massimo Zennaro, Nicola Branchini, Theodoros Damoulas"
collection: publications
permalink: /publication/felekis2024causal
date: 2024-04-01
venue: 'CLeaR 2024 (Causal Learning and Reasoning)'
paperurl: 'https://arxiv.org/abs/2312.08107'
---

Causal abstraction (CA) theory establishes formal criteria for relating multiple structural causal models (SCMs) at different levels of granularity by defining maps between them. These maps have significant relevance for real-world challenges such as synthesizing causal evidence from multiple experimental environments, learning causally consistent representations at different resolutions, and linking interventions across multiple SCMs. In this work, we propose COTA, the first method to learn abstraction maps from observational and interventional data without assuming complete knowledge of the underlying SCMs. In particular, we introduce a multi-marginal Optimal Transport (OT) formulation that enforces do-calculus causal constraints, together with a cost function that relies on interventional information. We extensively evaluate COTA on synthetic and real world problems, and showcase its advantages over non-causal, independent and aggregated COTA formulations. Finally, we demonstrate the efficiency of our method as a data augmentation tool by comparing it against the state-of-the-art CA learning framework, which assumes fully specified SCMs, on a real-world downstream task.
