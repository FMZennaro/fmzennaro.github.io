---
title: "SQL Injections and Reinforcement Learning: An Empirical Evaluation of the Role of Action Structure"
authors: "Manuel Del Verme, Åvald Åslaugson Sommervoll, Laszlo Erdodi, Simone Totaro, Fabio Massimo Zennaro"
collection: publications
permalink: /publication/delverme2021sql
date: 2021-06-30
venue: 'arXiv'
paperurl: ''
---

Penetration testing is a central problem in computer security, and recently, the application of machine learning techniques to this topic has gathered momentum. In this paper, we consider the problem of exploiting SQL injection vulnerabilities, and we represent it as a capture-the-flag scenario in which an attacker can submit strings to an input form with the aim of obtaining a flag token representing private information. We then model the attacker as a reinforcement learning agent that interacts with the server to learn an optimal policy leading to an exploit. We compare two agents: a simpler structured agent that relies on significant a priori knowledge and uses high-level actions; and a structureless agent that has minimal a priori knowledge and generates SQL statements. The comparison showcases the feasibility of developing agents that rely on less ad-hoc modeling and illustrates a possible direction to develop agents that may have wide applicability.
