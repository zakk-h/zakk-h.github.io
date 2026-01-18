---
title: "Real-Time Particle Collision Filtering with Unsupervised Learning on Custom FPGA Hardware"
authors: "Tanish Kumar, Zakk Heile, Nika Kiladze, Zesen Zhuang, Ashutosh Kotwal"
venue: "Duke Undergraduate Research Symposium"
date: 2024-04-30
category: conferences
order: 3
---

At CERN’s Large Hadron Collider, physicists recreate the conditions of the early universe to discover the constituents of dark matter by experimentally observing the products of proton-proton collisions. However, with protons colliding every 25 nanoseconds, computationally processing all the detector data from every collision is an impractical task. Our work is focused on designing and implementing a filtering algorithm that processes collision data, within the significant time constraint, to assess whether each collision warrants further study. 

We have determined that the most efficient way to do this is to use an unsupervised machine learning technique spread across a custom-designed, massively parallel computer. This device will use a novel graph-computing architecture, very different from the traditional Von Neumann architecture. Our focus is on the data produced by the innermost detectors, a set of five barrels made with silicon pixel sensors, with a resolution of ~15 microns. These detectors output a cloud of space points, representing the energy depositions of decay particles as they pass through the detector’s layers. To determine if the collision is worth studying further, we implement a novel algorithm at the hardware-level by designing field programmable gate arrays (FPGAs) – which are configurable integrated circuits. 

The filtering algorithm has two main stages: 1) appropriately structuring the cloud of space points to feed into the massive parallel computer and 2) reconstructing particle tracks at each node of the graph computer, given a slice of space points. The first stage of the algorithm creates patches (contiguous subsets) of space points given geometrical slices of the incoming data; these patches are passed to nodes of the computer, ensuring that all possibilities for particle tracks are accounted for. The second stage of the algorithm treats the space points as a graph, eliminating links via the application of a graph operator until the remaining linkages represent particle trajectories. These tracks are used to decide if the collision produced decay particles that are consistent with dark matter candidates. If found to be consistent, our artificial intelligence circuit would lead to more careful study and analysis of the collision. We aim for this project to be implemented in the next upgrade of the LHC to enable a unique and unprecedented search for dark matter signatures.
