---
title: "Analyzing and Storing Network Intrusion Detection Data using Bayesian Coresets: A Preliminary Study in Offline and Streaming Settings"
authors: "Fabio Massimo Zennaro"
collection: publications
permalink: /publication/zennaro2019analyzing
date: 2019-09-20
venue: 'ECML 2018 Workshop on Machine Learning for CyberSecurity'
paperurl: 'https://arxiv.org/abs/1906.08528'
---

In this paper we offer a preliminary study of the application of Bayesian coresets to network security data. Network intrusion detection is a field that could take advantage of Bayesian machine learning in modelling uncertainty and managing streaming data; however, the large size of the data sets often hinders the use of Bayesian learning methods based on MCMC. Limiting the amount of useful data is a central problem in a field like network traffic analysis, where large amount of redundant data can be generated very quickly via packet collection. Reducing the number of samples would not only make learning more feasible, but would also contribute to reduce the need for memory and storage. We explore here the use of Bayesian coresets, a technique that reduces the amount of data samples while guaranteeing the learning of an accurate posterior distribution using Bayesian learning.  We analyze how Bayesian coresets affect the accuracy of learned models, and how time-space requirements are traded-off, both in a static scenario and in a streaming scenario.
