---
title: 'Bayesian Coresets and Edward'
date: 2019-01-25
permalink: /posts/2019/01/coresets1/
tags:
  - coreset
  - edward
  - Bayes
---

Bayesian Coresets using Edward
======

Modern datasets often contain a large number of redundant samples, making the storing of data and the learning of models expensive. Coreset computation is an approach to reduce the amount of samples by selecting (and weighting) informative samples and discarding redundant ones. In Bayesian statistics, Bayesian coresets are designed to preserve a limited number of samples, while guaranteeing that the posterior learned from a coreset would be close to the posterior learned from the whole dataset. An excellent explanation of Bayesian coresets and their application is offered in this [video](https://www.youtube.com/watch?v=Moo4-KR5qNg) from ICML18.

In this notebook, we run a tutorial in which we explore the computation of Bayesian coresets as proposed in [this article](https://arxiv.org/abs/1710.05053) and [this article](https://arxiv.org/abs/1802.01737). In particular we integrate the [original code](https://github.com/trevorcampbell/bayesian-coresets) with the [Edward](http://edwardlib.org/) framework, thus exploiting the functions often by probabistic programming to further automate the computation of coresets. 

[Notebook here](https://github.com/FMZennaro/BayesianCoresets-Edward/blob/master/1.%20BayesianCoresets%20-%20Example%20with%20Edward.ipynb)
