---
permalink: /
title: "Zakk Heile"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi — I’m **Zakk Heile**. I am a researcher in Professor [Cynthia Rudin’s](https://users.cs.duke.edu/~cynthia/) **Interpretable Machine Learning Lab** at **Duke University**. I have been at Duke since 2023 as a **Computer Science and Mathematics** undergraduate, supported by the **Benjamin N. Duke Merit Scholarship**.

My current research focuses on **optimization problems for interpretable machine learning**, and I am also more broadly interested in **discrete optimization**. In many high-stakes settings, **optimal sparse models** can be competitive with black-box models while remaining interpretable, which is critical for responsible decision making and useful for machine learning practitioners as a way to understand model behavior and motivate principled feature engineering. I am particularly interested in **approximating Rashomon sets**, which are the sets of all optimal and near-optimal models within a given model class. Rashomon sets are useful for **characterizing variable importance across all near-optimal models**, for **making predictions without imputing missing values**, and for **analyzing disagreements between equally good models**, providing a more complete picture of uncertainty and structure than any single model. My latest work develops a family of algorithms for approximating Rashomon sets through **AND/OR graph search** and a **proxy-optimizer framework**. The key idea is to use fast decision tree algorithms to certify upper bounds on achievable subproblem quality, then refine those estimates as more of the search graph is built. This connects to **rollout** and **pilot algorithms** from **combinatorial optimization**, but with multiple outputs. I am also interested in **learning models that can choose to defer**, where an interpretable model predicts on cases it can handle confidently and passes the remaining cases to a more complicated model.

Previously, I have worked on **geometric data analysis** problems, including **rigid-invariant distances** for comparing distributions, point clouds, and shapes; on **interpretable natural language processing methods** for healthcare applications in traumatic brain injury; and on **real-time particle collision filtering** for deployment on **custom FPGA-based hardware** at CERN’s Large Hadron Collider.

---
