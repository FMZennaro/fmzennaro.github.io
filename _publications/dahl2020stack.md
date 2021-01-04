---
title: "Stack-based Buffer Overflow Detection using Recurrent Neural Networks"
authors: "William Arild Dahl, Laszlo Erdodi, Fabio Massimo Zennaro"
collection: publications
permalink: /publication/dahl2020stack
date: 2020-12-30
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2012.15116'
---

Detecting vulnerabilities in software is a critical challenge in the development and deployment of applications. One of the most known and dangerous vulnerabilities is stack-based buffer overflows, which may allow potential attackers to execute malicious code. In this paper we consider the use of modern machine learning models, specifically recurrent neural networks, to detect stack-based buffer overflow vulnerabilities in the assembly code of a program. Since assembly code is a generic and common representation, focusing on this language allows us to potentially consider programs written in several different programming languages. Moreover, we subscribe to the hypothesis that code may be treated as natural language, and thus we process assembly code using standard architectures commonly employed in natural language processing. We perform a set of experiments aimed at confirming the validity of the natural language hypothesis and the feasibility of using recurrent neural networks for detecting vulnerabilities. Our results show that our architecture is able to capture subtle stack-based buffer overflow vulnerabilities that strongly depend on the context, thus suggesting that this approach may be extended to real-world setting, as well as to other forms of vulnerability detection.
