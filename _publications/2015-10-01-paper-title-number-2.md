---
title: "Parallel Level-Set Based Approach for Etching Topography Simulation"
collection: publications
category: conferences
permalink: /publication/level-set-etching
date: 2025-07-15
venue: 'Proceedings of the International Conference on Computational Science'
paperurl: 'http://yin169.github.io/files/paper2.pdf'
bibtexurl: 'http://yin169.github.io/files/bibtex2.bib'
---

This paper introduces a parallel level set method framework for simulating etching topography in semiconductor manufacturing. The approach leverages high-order numerical schemes and OpenMP-based parallelization to achieve efficient and accurate simulations of complex etching processes.

## Abstract

Semiconductor etching simulation is crucial for predicting and optimizing manufacturing processes. This work presents a parallel 3D Level Set Method (LSM) framework for etching simulation featuring high-order spatial and temporal discretization, multi-threaded parallelization using OpenMP, robust handling of orientation-dependent etching, and validation against industrial standards. The implementation achieves super linear speedup and demonstrates high accuracy in capturing topological changes during etching processes.

## Key Contributions

1. Implementation of high-order numerical schemes for improved accuracy in etching simulations
2. Development of an efficient parallelization strategy using OpenMP
3. Comprehensive validation using quantitative metrics against industrial standards
4. Demonstration of super linear speedup in parallel execution