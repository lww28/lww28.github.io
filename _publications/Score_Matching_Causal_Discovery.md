---
title: "A Skewness-Based Criterion for Addressing Heteroscedastic Noise in Causal Discovery"
collection: publications
category: conferences
permalink: /publication/2024-11-01-skewscore
excerpt: "SkewScore introduces a skewness-based criterion to distinguish causal from anti-causal directions in models with heteroscedastic symmetric noise, and shows strong empirical and theoretical performance."
venue: "ICLR"
date: 2025-01-01
paperurl: https://openreview.net/pdf?id=zGzs5SIwT8
citation: 'Yingyu Lin*, Yuxing Huang*, Wenqin Liu*, Haoran Deng*, Ignavier Ng, Kun Zhang, Mingming Gong, Yi-An Ma, Biwei Huang. "A Skewness-Based Criterion for Addressing Heteroscedastic Noise in Causal Discovery." <i>ICLR 2025</i>.'
---
Real-world data often violates the equal-variance assumption (homoscedasticity), making it essential to account for heteroscedastic noise in causal discovery. In this work, we explore heteroscedastic symmetric noise models (HSNMs), where the effect Y is modeled as Y = f(X) + σ(X)N, with X as the cause and N as independent noise following a symmetric distribution. We introduce a novel crite- rion for identifying HSNMs based on the skewness of the score (i.e., the gradient of the log density) of the data distribution. This criterion establishes a computa- tionally tractable measurement that is zero in the causal direction but nonzero in the anticausal direction, enabling the causal direction discovery. We extend this skewness-based criterion to the multivariate setting and propose SkewScore, an algorithm that handles heteroscedastic noise without requiring the extraction of exogenous noise. We also conduct a case study on the robustness of SkewScore in a bivariate model with a latent confounder, providing theoretical insights into its performance. Empirical studies further validate the effectiveness of the proposed method.

