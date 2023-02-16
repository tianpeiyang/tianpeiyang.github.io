---
title: "An Efficient Transfer Learning Framework for Multiagent Reinforcement Learning"
collection: publications
permalink: /publication/2021-09-29-An Efficient Transfer Learning Framework for Multiagent Reinforcement Learning
date: 2021-09-29
venue: 'Thirty-fifth Conference on Neural Information Processing Systems (NeurIPS)'
---
[Bibtex](http://tianpeiyang.github.io/files/NeurIPS2021_maptf.bib)

This paper proposes a novel Multiagent Policy Transfer Framework (MAPTF) to improve MARL efficiency. MAPTF learns which agent's policy is the best to reuse for each agent and when to terminate it by modeling multiagent policy transfer as the option learning problem. Furthermore, in practice, the option module can only collect all agent's local experiences for update due to the partial observability of the environment. While in this setting, each agent's experience may be inconsistent with each other, which may cause the inaccuracy and oscillation of the option-value's estimation. Therefore, we propose a novel option learning algorithm, the successor representation option learning to solve it by decoupling the environment dynamics from rewards and learning the option-value under each agent's preference. MAPTF can be easily combined with existing deep RL and MARL approaches, and experimental results show it significantly boosts the performance of existing methods in both discrete and continuous state spaces.