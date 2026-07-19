---
title: "AGIPC: Adaptive In-Solve Algebraic Coarsening for GPU IPC"
excerpt: "A GPU-oriented method that dynamically reduces degrees of freedom within the Newton solve of implicit time integration, achieving up to 3x speedup over a state-of-the-art GPU IPC solver.<br/><img src='/images/agipc-teaser-1.jpg'>"
collection: portfolio
---

## AGIPC: Adaptive In-Solve Algebraic Coarsening for GPU IPC

**Publication:** ACM SIGGRAPH 2026 Conference Papers

**arXiv Paper:** [https://arxiv.org/abs/2605.04773](https://arxiv.org/abs/2605.04773)

### Authors
Xuan Wang, Zhaofeng Luo, Minchen Li, Taku Komura, Kemeng Huang

### Abstract
Implicit time integration is key to robustly simulating stiff materials and large deformations, but its performance is often dominated by repeatedly solving large linear systems. Adaptive coarsening can reduce this cost by concentrating degrees of freedom (DoF) where they are most needed, yet conventional explicit remeshing changes connectivity and vertex ordering, complicating parallel implementations and harming memory locality. We present algebraic adaptive in-solve coarsening, a GPU-oriented method that dynamically reduces DoF within the Newton solve of implicit time integration without explicit topological modification.

### Key Innovations
- **In-solve adaptive coarsening** expressed as a selective edge-collapse process governed by per-edge tags — no remeshing, no connectivity changes
- **Warp-level hash mapping scheme** that aggregates collapsible edges in parallel, grouping fine vertices into coarse super-nodes while protected edges preserve local detail
- **Algebraic system assembly** that maps and reduces fine-scale gradients and Hessians via efficient GPU reduction kernels; the coarse system is solved with preconditioned conjugate gradient (PCG) and prolongated back to the fine mesh
- **Seamless IPC integration** with barrier energy, exploiting GPU parallelism end-to-end and achieving up to **3x speedup** over a state-of-the-art GPU IPC solver with visually indistinguishable results

### Publication Information
- **Venue:** ACM SIGGRAPH 2026 Conference Papers
- **arXiv:** 2605.04773 (cs.GR, cs.PF)
- **Submitted:** May 6, 2026
- **DOI:** https://doi.org/10.48550/arXiv.2605.04773

### Resources
- [arXiv Paper](https://arxiv.org/abs/2605.04773)
- [Video](https://youtu.be/W4h_rcuEXvw)

![Image](/images/agipc-teaser-1.jpg)
