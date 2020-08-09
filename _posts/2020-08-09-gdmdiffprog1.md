---
title: 'Group Decision Making via Differentiable Programming'
date: 2020-08-09
permalink: /posts/2020-08-09-gdmdiffprog1
tags:
  - group decision making
  - consensus
  - differentiable programming
  - tensorflow
---

[Differentiable programming](https://towardsdatascience.com/deep-learning-from-a-programmers-perspective-aka-differentiable-programming-ec6e8d1b7c60) (also known as software 2.0) offers a novel approach to coding, focused on defining parametrized differentiable model to solve a problem instead of coding a precise algorithm. In this post we explore the use of this coding paradigm to solve the problem of consensus reaching in group-decision making (GDM). GDM studies the problem of aggregating the opinions of many experts/agents and the dynamics required to reach a consensus. 

We first define a model for aggregating preferences, and then we use differentiable programming to compute an optimal change to the original preferences that would lead to a consensus. We analyze the results and evaluate some altervative models. In our simulations we will use models, but we will underline how these can be easily extended.

[Notebook here](https://nbviewer.jupyter.org/github/FMZennaro/GDM/blob/master/differentiable_programming/Simulation1.ipynb)
