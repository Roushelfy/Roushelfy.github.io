---
title: "Robust and Efficient Penetration-Free Elastodynamics without Barriers"
excerpt: "A novel optimization approach for simulating elastic objects without physical penetration, achieving up to 103x speedup over existing methods.<br/><img src='/images/barrier_free_teaser.jpg'>"
collection: portfolio
---

## Robust and Efficient Penetration-Free Elastodynamics without Barriers

**Publication:** ACM Transactions on Graphics (SIGGRAPH 2026 Journal Track)

**Project Website:** [https://simulation-intelligence.github.io/barrier-free/](https://simulation-intelligence.github.io/barrier-free/)

**arXiv Paper:** [https://arxiv.org/abs/2512.12151v1/](https://arxiv.org/abs/2512.12151v1/)

### Authors
Juntian Zheng, Zhaofeng Luo, Minchen Li

### Abstract
This research presents an optimization approach for simulating elastic objects without physical penetration. The method addresses efficiency challenges in existing methods by:

1. **Eliminating logarithmic barrier functions** that cause poorly conditioned mathematical systems
2. **Resolving "time-of-impact locking"** that slows collision detection in complex scenes

### Key Innovations
- Novel framework using an **augmented Lagrangian solver** with adaptive multiplier updates instead of increasing penalty stiffness
- **Constraint filtering and decay mechanism** to keep the active set compact
- **GPU optimization** enabling up to **103x speedup** over GIPC on challenging, contact-rich benchmarks

### Publication Information
- **Venue:** ACM Transactions on Graphics (SIGGRAPH 2026 Journal Track)
- **arXiv:** 2512.12151v1
- **Submitted:** December 13, 2025
- **Category:** Computer Science > Graphics (cs.GR)
- **DOI:** https://doi.org/10.1145/3811035

### Open Source
The authors have committed to open-sourcing their code and supplementary materials.
