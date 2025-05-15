---
title: "Causal Discovery with Mixed Linear and Nonlinear Additive Noise Models: A Scalable Approach"
collection: publications
category: conferences
permalink: /publication/2023-11-01-lnmix
excerpt: "This paper proposes a causal discovery algorithm that identifies edge directions beyond Markov equivalence classes using the Jacobian of the score function, suitable for mixed linear and nonlinear mechanisms."
venue: "CLeaR"
date: 2024-01-01
paperurl: https://proceedings.mlr.press/v236/liu24b/liu24b.pdf
citation: 'Wenqin Liu, Biwei Huang, Erdun Gao, Qiuhong Ke, Howard Bondell, Mingming Gong. "Causal Discovery with Mixed Linear and Nonlinear Additive Noise Models: A Scalable Approach." <i>CLeaR 2024</i>.'
---
Estimating the structure of directed acyclic graphs (DAGs) from observational data is challeng- ing due to the super-exponential growth of the search space with the number of nodes. Previous research primarily focuses on identifying a unique DAG under specific model constraints in lin- ear or nonlinear scenarios. However, real-world scenarios often involve causal mechanisms with a mixture of linear and nonlinear characteristics, which has received limited attention in existing literature. Due to unidentifiability, existing algorithms relying on fully identifiable conditions may produce erroneous results. Although traditional methods like the PC algorithm can be employed to uncover such graphs, they typically yield only a Markov equivalence class. This paper intro- duces a novel causal discovery approach that extends beyond the Markov equivalence class, aiming to uncover as many edge directions as possible when the causal graph is not fully identifiable. Our approach exploits the second derivative of the log-likelihood in observational data, harness- ing scalable machine learning approaches to approximate the score function. Overall, our approach demonstrates competitive accuracy comparable to current state-of-the-art techniques while offering a significant improvement in computational speed.
