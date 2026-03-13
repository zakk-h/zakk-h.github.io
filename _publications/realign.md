---
title: "Align Representations, Not Points: Efficient Rigid Invariant Transport Distance"
authors: "Zakk Heile, Peilin He, Jayson Tran, Alice Wang, Shrikant Chand"
venue: "ICLR Re-Align"
date: 2026-4-30
output_type: "Conference paper"
category: papers
paperurl: "https://openreview.net/pdf?id=hLG8HynoTk"
order: 2
---

Comparing probability measures modulo unknown rigid transformations is a central challenge in geometric data analysis. Classical optimal transport (OT) distances, including Wasserstein and sliced Wasserstein, are sensitive to rotations and reflections, whereas Gromov-Wasserstein (GW) and Procrustes-Wasserstein (PW) distances are invariant to isometries but computationally prohibitive for large datasets. 

We introduce Rigid-Invariant Sliced Wasserstein via Independent Embeddings (RISWIE), a scalable distance that combines the invariance of NP-hard approaches with the efficiency of projection-based OT. RISWIE utilizes data-adaptive bases and matches optimal signed permutations along axes according to distributional similarity to achieve rigid invariance with nearly linear complexity in the sample size. 

We prove bounds relating RISWIE to GW in special cases and demonstrate dimension-independent statistical stability. Our experiments on cellular imaging and 3D human meshes demonstrate that RISWIE outperforms GW and PW in clustering tasks and discriminative capability while significantly reducing runtime.

