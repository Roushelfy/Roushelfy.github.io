---
title: "An Overlapping Schwarz Space-Time Refinement Framework for Material Point Method"
collection: publications
permalink: /publications/schwarz-mpm/
date: 2026-05-09
venue: "arXiv preprint"
publication_status: "Preprint"
paperurl: "https://arxiv.org/abs/2605.09097"
excerpt: "Overlapping coarse and fine MPM subdomains enable modular local refinement in space and time for localized deformation and contact."
---

**Zhaofeng Luo**, Minchen Li, Yupeng Jiang

**arXiv preprint, 2026.**

OS-MPM combines overlapping coarse and fine subdomains with different spatial and temporal resolutions. An MPM-specific Schwarz iteration couples the subdomains through mass-weighted spatial transmission and temporal interpolation, retaining standard MPM discretizations within each subdomain.

Benchmarks include a gravity-driven cantilever, Hertzian contact, and an elastic inclusion. The inclusion benchmark shows **up to 9.15× lower computational cost** than a single-domain fine simulation at comparable accuracy at the finest tested resolutions.

[Paper](https://arxiv.org/abs/2605.09097) · [Project overview]({{ '/portfolio/schwarz-mpm/' | relative_url }})
