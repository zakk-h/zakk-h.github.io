---
title: "Context-Aware Filtering of Unstructured Radiology Reports by Anatomical Region"
authors: "Zakk Heile, Pranav Manjunath, Brian Lerner, Samuel Berchuck, Monica Agrawal, Timothy W. Dunn"
venue: "Machine Learning for Health (ML4H)"
date: 2025-01-01
category: conferences
paperurl: "https://openreview.net/pdf?id=zgy9zuhtX2"
order: 1
---

Radiology reports contain essential clinical information but are often stored as unstructured free text. In trauma settings, multiple imaging studies (e.g., CT head, facial bones, and cervical spine) may be bundled into a single report that consolidates findings from all examinations into one jointly written document. As a result, individual sentences may reference ambiguous or overlapping anatomy (e.g., “there is a fracture”), making sentence-level anatomical classification essential for downstream tasks.

We develop **context-aware classical models with targeted feature engineering** to filter radiology reports by anatomical region, retaining only findings relevant to a specified anatomy. Leveraging the precision of clinical language, our approach **outperforms trained neural networks and large pre-trained language models**, while requiring only a small amount of labeled training data.

We demonstrate that the learned model weights **generalize effectively to MIMIC-IV radiology reports** without retraining and achieve near-optimal performance in both sensitivity and specificity. These results make our approach practical, reproducible, and well-suited for deployment in new clinical settings.
