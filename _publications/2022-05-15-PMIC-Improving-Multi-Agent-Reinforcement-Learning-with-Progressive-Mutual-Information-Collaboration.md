---
title: "PMIC: Improving Multi-Agent Reinforcement Learning with Progressive Mutual Information Collaboration"
collection: publications
permalink: /publication/2022-05-15-PMIC-Improving-Multi-Agent-Reinforcement-Learning-with-Progressive-Mutual-Information-Collaboration
date: 2022-05-15
venue: 'The Thirty-ninth International Conference on Machine Learning (ICML)'
---
[Bibtex](http://tianpeiyang.github.io/files/ICML2022_pmic.bib)

Learning to collaborate is critical in multi-agent reinforcement learning (MARL). A number of previous works promote collaboration by maximizing the correlation of agents' behaviors, which is typically characterised by mutual information (MI) in different forms. However, in this paper, we reveal that strong correlation can emerge from sub-optimal collaborative behaviors, and simply maximizing the MI can, surprisingly, hinder the learning towards better collaboration. To address this issue, we propose a novel MARL framework, called Progressive Mutual Information Collaboration (PMIC), for more effective MI-driven collaboration. In PMIC, we use a new collaboration criterion measured by the MI between global states and joint actions. Based on the criterion, the key idea of PMIC is maximizing the MI associated with superior collaborative behaviors and minimizing the MI associated with inferior ones. The two MI objectives play complementary roles by facilitating learning towards better collaborations while avoiding falling into sub-optimal ones. Specifically, PMIC stores and progressively maintains sets of superior and inferior interaction experiences, from which dual MI neural estimators are established. Experiments on a wide range of MARL benchmarks show the superior performance of PMIC compared with other algorithms.