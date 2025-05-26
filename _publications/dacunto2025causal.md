---
title: "Causal Abstraction Learning based on the Semantic Embedding Principle"
authors: "Gabriele D'Acunto, Fabio Massimo Zennaro, Yorgos Felekis, Paolo Di Lorenzo"
collection: publications
permalink: /publication/dacunto2025causal
date: 2025-02-01
venue: 'ICML 2025 (International Conference on Machine Learning)'
paperurl: 'https://arxiv.org/abs/2502.00407'
---

Structural causal models (SCMs) allow us to investigate complex systems at multiple levels of resolution. The causal abstraction (CA) framework formalizes the mapping between high- and low-level SCMs. We address CA learning in a challenging and realistic setting, where SCMs are inaccessible, interventional data is unavailable, and sample data is misaligned. A key principle of our framework is semantic embedding, formalized as the high-level distribution lying on a subspace of the low-level one. This principle naturally links linear CA to the geometry of the Steifel manifold. We present a category-theoretic approach to SCMs that enables the learning of a CA by finding a morphism between the low- and high-level probability measures, adhering to the semantic embedding principle. Consequently, we formulate a general CA learning problem. As an application, we solve the latter problem for linear CA; considering Gaussian measures and the Kullback-Leibler divergence as an objective. Given the nonconvexity of the learning task, we develop three algorithms building upon existing paradigms for Riemannian optimization. We demonstrate that the proposed methods succeed on both synthetic and real-world brain data with different degrees of prior information about the structure of CA.
