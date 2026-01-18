---
title: "Scalable Rigid-Invariant Distance for Shape Matching and Alignment"
authors: "Zakk Heile, Peilin He, Jayson Tran, Ruiling Wang, Shrikant Chand"
venue: "NeurIPS Workshop for Imageomics: Discovering Biological Knowledge from Images Using AI"
date: 2025-12-01
category: conferences
paperurl: "https://openreview.net/pdf?id=yxZmNuLwa3"
order: 5
---

Comparing probability distributions derived from biological images requires distances that are geometrically grounded and invariant to orientation. Classical optimal transport (OT) distances are sensitive to rotations, while Gromov–Wasserstein (GW) offers invariance but is computationally prohibitive for large datasets.

We introduce **Rigid-Invariant Sliced Wasserstein via Independent Embeddings (RISWIE)**, a scalable pseudometric that achieves rigid invariance by aligning data-adaptive embeddings through optimal signed permutations at negligible computational cost. Evaluated on **2D HuBMAP tissue slices** and **3D MPI-FAUST human meshes**, RISWIE achieves **95.8% accuracy** with over **10⁴× speedup** relative to GW and an **AUC of 0.94** for human pose matching.

Beyond efficiency, RISWIE’s optimization yields **explicit axis alignments** that are directly usable for downstream analysis, making it a practical and interpretable distance for large-scale geometric data analysis.
