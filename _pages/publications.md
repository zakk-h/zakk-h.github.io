---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my papers on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Papers

**Zakk Heile**, Hayden McTavish, Margo Seltzer, and Cynthia Rudin. [Multistage Defer Trees for Hybrid Interpretability: If at First You Can’t Succeed, Tree Again.](https://arxiv.org/abs/2606.30995) *arXiv preprint*, 2026.

**Abstract.** Recent work has shown that well-optimized individual decision trees can match complex black box models in some settings, primarily in noisy domains. For the remaining settings, complex ensembled compositions of trees often achieve higher accuracy at the cost of interpretability. We introduce Multistage Defer Trees: a sequence of sparse decision trees that each make predictions for most samples, while deferring a small proportion to the next tree in the sequence or, ultimately, to a black box. We demonstrate that MDTs can match the performance of complex tree-based ensembles while routing most samples through only one or a small number of sparse decision trees, expanding the accuracy–interpretability frontier in settings where single-tree methods remain insufficient.

**Zakk Heile**, Hayden McTavish, Varun Babbar, Margo Seltzer, and Cynthia Rudin. [From Rashomon Theory to PRAXIS: Efficient Decision Tree Rashomon Sets.](https://arxiv.org/abs/2606.00202) *International Conference on Machine Learning (ICML)*, 2026.

**Abstract.** Standard machine learning pipelines often admit many near-optimal models. These "Rashomon sets" pose a range of challenges and opportunities for uncertainty-aware, robust decision making. They allow users to incorporate domain knowledge and preferences that would otherwise be difficult to specify directly in an objective, and they quantify diversity among valid models for a given training dataset and objective function. However, computation of Rashomon sets, even for simple, interpretable model classes such as sparse decision trees, continues to require immense memory and runtime resources. We present PRAXIS, an algorithm to approximate this Rashomon set with orders of magnitude improvement in runtime and memory usage. We validate that PRAXIS regularly recovers almost all of the full Rashomon set. PRAXIS allows researchers and practitioners to scalably model the Rashomon set for real-world datasets.

**Zakk Heile**, Pranav Manjunath, Brian Lerner, Samuel Berchuck, Monica Agrawal, and Timothy W. Dunn. [Context-Aware Filtering of Unstructured Radiology Reports by Anatomical Region.](https://openreview.net/pdf?id=zgy9zuhtX2) *Machine Learning for Health (ML4H)*, 2025.

**Abstract.** Radiology reports contain essential clinical information but are often stored as unstructured free text. In trauma settings, multiple imaging studies may be bundled into a single report that consolidates findings from all examinations into one jointly written document. As a result, individual sentences may reference ambiguous or overlapping anatomy, making sentence-level anatomical classification essential for downstream tasks. We develop context-aware classical models with targeted feature engineering to filter radiology reports by anatomical region, retaining only findings relevant to a specified anatomy. Leveraging the precision of clinical language, our approach outperforms trained neural networks and large pre-trained language models while requiring only a small amount of labeled training data. We demonstrate that the learned model weights generalize effectively to MIMIC-IV radiology reports without retraining and achieve near-optimal performance in both sensitivity and specificity.

**Zakk Heile**, Peilin He, Jayson Tran, Alice Wang, and Shrikant Chand. [Rigid-Invariant Sliced Wasserstein via Independent Embeddings.](https://openreview.net/pdf?id=hLG8HynoTk) *ICLR GRaM Proceedings*, 2026.

**Abstract.** Comparing probability measures modulo unknown rigid transformations is a central challenge in geometric data analysis. Classical optimal transport (OT) distances, including Wasserstein and sliced Wasserstein, are sensitive to rotations and reflections, whereas Gromov-Wasserstein (GW) and Procrustes-Wasserstein (PW) distances are invariant to isometries but computationally prohibitive for large datasets. We introduce Rigid-Invariant Sliced Wasserstein via Independent Embeddings (RISWIE), a scalable distance that combines the invariance of NP-hard approaches with the efficiency of projection-based OT. RISWIE utilizes data-adaptive bases and matches optimal signed permutations along axes according to distributional similarity to achieve rigid invariance with nearly linear complexity in the sample size. We prove bounds relating RISWIE to GW in special cases and demonstrate dimension-independent statistical stability. Our experiments on cellular imaging and 3D human meshes demonstrate that RISWIE outperforms GW and PW in clustering tasks and discriminative capability while significantly reducing runtime.


**Zakk Heile**, Peilin He, Jayson Tran, Alice Wang, and Shrikant Chand. [Align Representations, Not Points: Efficient Rigid Invariant Transport Distance.](https://openreview.net/pdf?id=3yiQT4FWFl) *ICLR Re-Align*, 2026.

**Zakk Heile**, Peilin He, Jayson Tran, Ruiling Wang, and Shrikant Chand. [Scalable Rigid-Invariant Distance for Shape Matching and Alignment.](https://openreview.net/pdf?id=yxZmNuLwa3) *NeurIPS Workshop for Imageomics: Discovering Biological Knowledge from Images Using AI*, 2025.

**Zakk Heile**, Varun Babbar, Hayden McTavish, and Cynthia Rudin. [Efficient Rashomon Set Approximation for Decision Trees.](https://openreview.net/pdf?id=JlnpgWUXfS) *NeurIPS Workshop on Mathematical Foundations and Operational Integration of Machine Learning for Uncertainty-Aware Decision-Making (MLxOR)*, 2025.

**Abstract.** Standard machine learning pipelines often admit many near-optimal models. These Rashomon sets pose both challenges and opportunities for uncertainty-aware and robust decision making: they enable incorporation of domain knowledge and user preferences that are difficult to encode directly in an objective, and they quantify diversity among plausible models and predictions for a given dataset and loss. Despite their utility, Rashomon sets have been difficult to compute in practice due to severe computational intractability, even for simple and interpretable model classes such as sparse decision trees. We introduce LicketyRESPLIT, an algorithm for efficiently approximating the Rashomon set of decision trees with orders-of-magnitude improvements in runtime and memory usage. We empirically show that LicketyRESPLIT regularly recovers nearly all of the full Rashomon set, substantially expanding the practical feasibility of Rashomon set analysis for researchers and practitioners.

# Presentations

**Zakk Heile** and Jayson Tran. Rigid-Invariant Sliced Wasserstein via Independent Embeddings. Presentation at the *Joint Mathematics Meetings (JMM)*, 2026.

**AI4TBI Bass Connections Team.** Discovering AI Applications for Traumatic Brain Injury Care. Presentation at the *Bass Connections Research Showcase, Duke University*, 2025.

**Abstract.** We present a mixed-methods investigation of traumatic brain injury (TBI) care at Duke University, aimed at identifying opportunities for responsible and clinically aligned AI decision support. The project combines rapid qualitative analysis of clinician interviews and shadowing across the TBI care pathway with large-scale curation and quality assurance of multimodal electronic health record data. Findings highlight key documentation challenges, sources of clinical variability, and stakeholder-guided requirements for AI deployment, alongside the construction of a curated TBI dataset to support future modeling and benchmarking.

Tanish Kumar, **Zakk Heile**, Nika Kiladze, Zesen Zhuang, and Ashutosh Kotwal. Real-Time Particle Collision Filtering with Unsupervised Learning on Custom FPGA Hardware. Presentation at the *Duke Research Symposium*, 2024.

**Abstract.** At CERN’s Large Hadron Collider, physicists recreate the conditions of the early universe to discover the constituents of dark matter by experimentally observing the products of proton-proton collisions. However, with protons colliding every 25 nanoseconds, computationally processing all detector data from every collision is impractical. Our work focuses on designing and implementing a filtering algorithm that processes collision data under significant time constraints to assess whether each collision warrants further study.

We use an unsupervised machine learning technique implemented on custom-designed, massively parallel hardware. The device uses a graph-computing architecture that differs from the traditional Von Neumann architecture. Our focus is on data produced by the innermost detectors, a set of five barrels made with silicon pixel sensors. These detectors output a cloud of space points representing energy depositions of decay particles as they pass through the detector layers.

The filtering algorithm has two main stages: first, structuring the cloud of space points into geometrical patches suitable for the parallel computer; second, reconstructing particle tracks at each node of the graph computer. The second stage treats the space points as a graph, eliminating links through a graph operator until the remaining linkages represent particle trajectories. These tracks are used to decide whether the collision produced decay particles consistent with dark matter candidates. The long-term goal is for this project to be implemented in a future LHC upgrade to enable a unique and unprecedented search for dark matter signatures.
