---
title: "On the Use of Sparse Filtering for Covariate Shift Adaptation"
authors: "Fabio Massimo Zennaro, Ke Chen"
collection: publications
permalink: /publication/zennaro2016use
date: 2016-07-22
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/1607.06781'
---

In this paper we formally analyse the use of sparse filtering algorithms to perform covariate shift adaptation. We provide a theoretical analysis of sparse filtering by evaluating the conditions required to perform covariate shift adaptation. We prove that sparse filtering can perform adaptation only if the conditional distribution of the labels has a structure explained by a cosine metric. To overcome this limitation, we propose a new algorithm, named periodic sparse filtering, and carry out the same theoretical analysis regarding covariate shift adaptation. We show that periodic sparse filtering can perform adaptation under the looser and more realistic requirement that the conditional distribution of the labels has a periodic structure, which may be satisfied, for instance, by user-dependent data sets. We experimentally validate our theoretical results on synthetic data. Moreover, we apply periodic sparse filtering to real-world data sets to demonstrate that this simple and computationally efficient algorithm is able to achieve competitive performances.
