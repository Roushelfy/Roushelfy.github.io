---
title: "An Overlapping Schwarz Space-Time Refinement Framework for Material Point Method"
excerpt: "A modular MPM framework for overlapping coarse and fine subdomains with local refinement in both space and time. Preprint, 2026."
collection: portfolio
permalink: /portfolio/schwarz-mpm/
display_order: 4
---

**arXiv preprint, 2026.** [Paper](https://arxiv.org/abs/2605.09097)

### Authors

**Zhaofeng Luo**, Minchen Li, Yupeng Jiang

### Overview

OS-MPM targets simulations where deformation, contact, and geometric nonlinearity are strongly localized. It divides the domain into overlapping coarse and fine subdomains with heterogeneous spatial and temporal resolutions, so that computation can be concentrated in the regions that need it.

### Method

An overlapping Schwarz iteration couples standard MPM discretizations through mass-weighted spatial transmission and temporal interpolation for sub-cycling. The framework handles nonmatching grids through interface operators, preserving the modular structure of each MPM subdomain.

### Evaluation

Numerical examples include a gravity-driven cantilever beam, Hertzian contact, and an elastic inclusion. In the inclusion benchmark, the framework reduces computational cost by **up to 9.15×** relative to a single-domain fine simulation, with comparable or slightly lower error at the finest tested resolutions.

[Paper](https://arxiv.org/abs/2605.09097) · [Publication record]({{ '/publications/schwarz-mpm/' | relative_url }})
