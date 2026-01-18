---
title: "Rigid-Invariant Sliced Wasserstein via Independent Embeddings"
authors: "Peilin He, Zakk Heile, Jayson Tran, Alice Wang, Shrikant Chand"
venue: "arXiv preprint arXiv:2510.10233"
date: 2025-10-11
category: manuscripts
paperurl: "https://arxiv.org/abs/2510.10233"
---

Comparing probability measures when their supports are related by an unknown rigid transformation is an important challenge in geometric data analysis, arising in shape matching and machine learning. Classical optimal transport (OT) distances, including Wasserstein and sliced Wasserstein, are sensitive to rotations and reflections, while Gromov–Wasserstein (GW) is invariant to isometries but computationally prohibitive for large datasets.

We introduce **Rigid-Invariant Sliced Wasserstein via Independent Embeddings (RISWIE)**, a scalable pseudometric that combines the invariance of NP-hard approaches with the efficiency of projection-based OT. RISWIE leverages data-adaptive bases and matches optimal signed permutations along axes according to distributional similarity, achieving rigid invariance with near-linear complexity in the sample size.

We prove bounds relating RISWIE to GW in special cases and empirically demonstrate dimension-independent statistical stability. Experiments on cellular imaging and 3D human meshes show that RISWIE outperforms GW in clustering and discriminative tasks while reducing runtime by orders of magnitude.
