---
title: "Cross-domain Adaptive Transfer Reinforcement Learning Based on State-Action Correspondence"
collection: publications
permalink: /publication/2022-05-15-Cross-domain-Adaptive-Transfer-Reinforcement-Learning-Based-on-State-Action-Correspondence
date: 2022-05-15
venue: 'The Thirty-eighth Conference on Uncertainty in Artificial Intelligence (UAI)'
---
[Bibtex](http://tianpeiyang.github.io/files/UAI2022_cat.bib)

Despite the impressive success achieved in various domains, deep reinforcement learning (DRL) is still faced with the sample inefficiency problem. Transfer learning (TL), which leverages prior knowledge from different but related tasks to accelerate the target task learning, has emerged as a promising direction to improve RL efficiency. The majority of prior work considers TL across tasks with the same state-action spaces, while transferring across domains with different state-action spaces is relatively unexplored. Furthermore, such existing cross-domain transfer approaches only enable transfer from a single source policy, leaving open the important question of how to best transfer from multiple source policies. This paper proposes a novel framework called Cross-domain Adaptive Transfer (CAT) to accelerate DRL. CAT learns the state-action correspondence from each source task to the target task and adaptively transfers knowledge from multiple source task policies to the target policy. CAT can be easily combined with existing DRL algorithms and experimental results show that CAT significantly accelerates learning and outperforms other cross-domain transfer methods on multiple continuous action control tasks.