---
title: "Rigid-Invariant Sliced Wasserstein via Independent Embeddings"
authors: "Zakk Heile, Jayson Tran, Peilin He, Alice Wang"
venue: "Joint Mathematics Meetings (JMM)"
date: 2026-01-01
category: conferences
---

Comparing probability measures whose supports are related by an unknown rigid transformation is a fundamental challenge in geometric data analysis, arising in shape matching and machine learning. Classical optimal transport (OT) distances, including Wasserstein and sliced Wasserstein, are sensitive to rotations and reflections, while Gromov–Wasserstein (GW) is invariant to isometries but computationally prohibitive for large datasets.

We present **Rigid-Invariant Sliced Wasserstein via Independent Embeddings (RISWIE)**, a scalable pseudometric that combines the invariance properties of NP-hard approaches with the efficiency of projection-based OT. RISWIE constructs data-adaptive bases and matches optimal signed permutations along axes according to distributional similarity, achieving rigid invariance with **near-linear complexity in the sample size**.

We prove bounds relating RISWIE to GW in the Gaussian case and empirically demonstrate **dimension-independent statistical stability**. Experiments on cellular imaging data and 3D human meshes show that RISWIE outperforms GW in clustering and discriminative tasks while significantly reducing runtime.

**Presenting authors:** Zakk Heile, Jayson Tran  
