---
layout: pubs
title:  "ReSBM: Region-based Scale and Minimal-Level Bootstrapping Management for FHE via Min-Cut"
brief:  "ReSBM: CKKS Scale & Noise Management - ASPLOS 2025"
date:   2025-03-30
author: Yan Liu
---

### Abstract

The RNS-CKKS scheme in Fully Homomorphic Encryption (FHE) supports crucial features for privacy-preserving machine learning, such as fixed-point arithmetic and SIMD-style vectorization. Yet, managing the escalation of ciphertext scales from homomorphic multiplications, which risks capacity overflow, along with bootstrapping, presents significant challenges. These complexities are exacerbated by the need to efficiently handle scale and bootstrapping at compile time while ensuring rapid encrypted inference.

In this paper, we present ReSBM, a novel compiler technique that simultaneously optimizes scale and bootstrapping for encrypted inference under RNS-CKKS. By partitioning a program’s data flow graph (DFG) into regions with a uniform multiplicative depth of one, ReSBM ensures that placements of Scale Management Operations (SMOs) and bootstraps affect only the latency of a region, not the scales and levels of its live-out ciphertexts. Our region-based approach tackles the NP-hard challenge of optimal bootstrapping placement with hierarchical strategies: (1) optimal intra-region SMO and bootstrapping placement using min-cut, (2) bootstrapping-guided rescaling region identification across a sequence of regions, culminating in tentative bootstrapping at two terminal regions, and (3) minimal-level bootstrap placement across the DFG, elevating ciphertexts only to the necessary minimal level. Validation across a variety of complex models on CPUs shows that ReSBM not only compiles these models more rapidly than a leading method but also boosts encrypted inference efficiency by an average of 12.1% when compared to another leading method. Consequently, ReSBM substantially improves the practical deployment of large models for encrypted inference, surpassing existing methods in terms of both compilation speed and inference performance.

### ACM Reference Format

Yan Liu, Jianxin Lai*, Long Li, Tianxiang Sui, Linjie Xiao, Peng Yuan, Xiaojing Zhang, Qing Zhu, Wenguang Chen*, and Jingling Xue. 2025. ReSBM: Region-based Scale and Minimal-Level Bootstrapping Management for FHE via Min-Cut. In Proceedings of the 30th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 1 (ASPLOS ’25), March 30–April 3, 2025, Rotterdam, Netherlands. ACM, New York, NY, USA, 16 pages. https://doi.org/10.1145/3669940.3707276

[[Paper Download]](https://dl.acm.org/doi/abs/10.1145/3669940.3707276) 