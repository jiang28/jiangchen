---
title: "Modeling Real Estate Dynamics Using Temporal Encoding"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-6
excerpt: "Chen Jiang, Jingjing Li, Wenlu Wang, Wei-Shinn Ku"
date:  2021/11/02
venue: 'SIGSPATIAL: Proceedings of the 29th International Conference on Advances in Geographic Information Systems'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3474717.3484254'
---

Deep learning has assisted modern life in various ways. One example is that accurate economic prediction helps people better allocate and distribute their resources. In the U.S., home prices have been accelerating during the COVID-19 pandemic and climbed 13.3% in March 2021 from the previous year. Real estate market prediction is critical for home buyers and investors to make wise decisions. In some circumstances, accurate predictions on home prices are more important than usual in helping decision-makers to reduce financial mistakes.
In this paper, we introduce a large-scale real estate-related dataset for the value prediction task. It consists of numerical real estate price history data from Zillow1 and survey data from Census Bureau public dataset. Our goal is to utilize data from different levels to model the real-estate dynamics with temporal and non-temporal data. We propose to embed sequential temporal features using a transformer and combine them with non-temporal features for subsequent prediction tasks, and evaluate using a different number of classes L ϵ {2, 3, 4, 5}. As an example, when L = 2, we have achieved 93.5% accuracy with our proposed model, and when L = 3, our proposed model has achieved 90.1% prediction accuracy. The results suggest that the proposed model overall outperforms all the baseline models.
