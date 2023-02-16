---
title: "GALOIS: Boosting Deep Reinforcement Learning via Generalizable Logic Synthesis"
collection: publications
permalink: /publication/2022-12-01-GALOIS Boosting Deep Reinforcement Learning via Generalizable Logic Synthesis
date: 2022-12-01
venue: 'Thirty-sixth Conference on Neural Information Processing Systems (NeurIPS)'
---
[Bibtex](http://tianpeiyang.github.io/files/NeurIPS2022_Galois.bib)

Despite achieving superior performance in human-level control problems, unlike humans, deep reinforcement learning (DRL) lacks high-order intelligence (e.g., logic deduction and reuse), thus it behaves ineffectively than humans regarding learning and generalization in complex problems. Previous works attempt to directly synthesize a white-box logic program as the DRL policy, manifesting logic-driven behaviors. However, most synthesis methods are built on imperative or declarative programming, and each has a distinct limitation, respectively. In this paper, we combine the above two paradigms together and propose a novel Generalizable Logic Synthesis (GALOIS) framework to synthesize hierarchical and strict cause-effect logic programs. GALOIS leverages the program sketch and defines a new sketch-based hybrid program language for guiding the synthesis. Based on that, GALOIS proposes a sketch-based program synthesis method to automatically generate white-box programs with generalizable and interpretable cause-effect logic. Extensive evaluations on various decision-making tasks with complex logic demonstrate the superiority of GALOIS over mainstream baselines regarding the asymptotic performance, generalizability, and great knowledge reusability across different environments.