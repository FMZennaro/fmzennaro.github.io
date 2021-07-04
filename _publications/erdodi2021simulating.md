---
title: "Simulating SQL Injection Vulnerability Exploitation Using Q-Learning Reinforcement Learning Agents"
authors: "Laszlo Erdodi,  Åvald Åslaugson Sommervoll, Fabio Massimo Zennaro"
collection: publications
permalink: /publication/erdodi2021simulating
date: 2021-01-08
venue: 'Journal of Information Security and Applications'
paperurl: 'https://arxiv.org/abs/2101.03118'
---

In this paper, we propose a first formalization of the process of exploitation of SQL injection vulnerabilities. We consider a simplification of the dynamics of SQL injection attacks by casting this problem as a security capture-the-flag challenge. We model it as a Markov decision process, and we implement it as a reinforcement learning problem. We then deploy different reinforcement learning agents tasked with learning an effective policy to perform SQL injection; we design our training in such a way that the agent learns not just a specific strategy to solve an individual challenge but a more generic policy that may be applied to perform SQL injection attacks against any system instantiated randomly by our problem generator. We analyze the results in terms of the quality of the learned policy and in terms of convergence time as a function of the complexity of the challenge and the learning agent's complexity. Our work fits in the wider research on the development of intelligent agents for autonomous penetration testing and white-hat hacking, and our results aim to contribute to understanding the potential and the limits of reinforcement learning in a security environment.
