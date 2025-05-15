---
title: "MissScore: High-Order Score Estimation in the Presence of Missing Data"
collection: publications
category: conferences
permalink: /publication/2025-05-01-missscore
excerpt: "MissScore is a novel algorithm that enables causal discovery with incomplete datasets by leveraging high-order score function estimation, achieving state-of-the-art results in simulations."
venue: "ICML"
date: 2025-05-01
paperurl: /files/ICML_MissScore.pdf
citation: 'Wenqin Liu, Haonan Hou, Erdun Gao, Biwei Huang, Qiuhong Ke, Howard Bondell, Mingming Gong. "MissScore: High-Order Score Estimation in the Presence of Missing Data." <i>ICML 2025</i>.'
---
Score-based generative models are essential in various machine learning applications, with strong capabilities in generation quality. In particular, high-order derivatives (scores) of data density offer deep insights into data distributions, building on the proven effectiveness of first-order scores for modeling and generating synthetic data, unlocking new possibilities for applications. However, learning them typically requires complete data, which is often unavailable in fields such as healthcare and finance due to factors such as data corruption, loss during collection, or incomplete reporting. To tackle this challenge, we introduce MissScore, a novel framework for estimating high-order scores in the presence of missing data. We derive objective functions for estimating high-order scores under different missing data mechanisms and propose a new algorithm specifically designed to handle missing data effectively. Our empirical results demonstrate that MissScore efficiently and accurately learns the high-order scores from incomplete data, while also improving sampling speed and data quality, as validated through several downstream tasks.
