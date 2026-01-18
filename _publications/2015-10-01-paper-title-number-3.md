---
title: "Efficient Rashomon Set Approximation for Decision Trees"
authors: "Zakk Heile, Varun Babbar, Hayden McTavish, Cynthia Rudin"
venue: "NeurIPS 2025 Workshop on Mathematical Foundations and Operational Integration of Machine Learning for Uncertainty-Aware Decision-Making (MLxOR)"
date: 2025-12-01
category: conferences
paperurl: "https://openreview.net/pdf?id=JlnpgWUXfS"
---

Standard machine learning pipelines often admit many near-optimal models. These **Rashomon sets** pose both challenges and opportunities for uncertainty-aware and robust decision making: they enable incorporation of domain knowledge and user preferences that are difficult to encode directly in an objective, and they quantify diversity among plausible models and predictions for a given dataset and loss.

Despite their utility, Rashomon sets have been difficult to compute in practice due to **severe computational intractability**, even for simple and interpretable model classes such as sparse decision trees. Existing methods require prohibitive memory and runtime resources, limiting applicability to real-world datasets.

We introduce **LicketyRESPLIT**, an algorithm for efficiently approximating the Rashomon set of decision trees with **orders-of-magnitude improvements in runtime and memory usage**. We empirically show that LicketyRESPLIT regularly recovers **nearly all of the full Rashomon set**, substantially expanding the practical feasibility of Rashomon set analysis for researchers and practitioners.
