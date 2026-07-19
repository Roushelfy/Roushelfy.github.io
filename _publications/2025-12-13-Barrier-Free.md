---
title: "Robust and Efficient Penetration-Free Elastodynamics without Barriers"
collection: publications
permalink: /publications/2025-12-13-Barrier-Free
date: 2025-12-13
venue: "ACM Transactions on Graphics (SIGGRAPH 2026 Journal Track)"
paperurl: "https://arxiv.org/abs/2512.12151v1/"
---
Juntian Zheng, Zhaofeng Luo, Minchen Li

**Accepted to the SIGGRAPH 2026 journal track (ACM Transactions on Graphics).**

We present an optimization approach for simulating elastic objects without physical penetration. Our method addresses efficiency challenges in existing methods by eliminating logarithmic barrier functions that cause poorly conditioned mathematical systems and resolving "time-of-impact locking" that slows collision detection in complex scenes.

**Key Innovations:**
- Novel framework using an augmented Lagrangian solver with adaptive multiplier updates instead of increasing penalty stiffness
- Constraint filtering and decay mechanism to keep the active set compact
- GPU optimization enabling up to **103x speedup** over GIPC on challenging, contact-rich benchmarks

The authors have committed to open-sourcing their code and supplementary materials.

[Project Page](https://simulation-intelligence.github.io/barrier-free/) | [arXiv Paper](https://arxiv.org/abs/2512.12151v1/) | [DOI](https://doi.org/10.1145/3811035)

![Image](/images/barrier_free_teaser.jpg)
