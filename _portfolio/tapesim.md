---
title: "TapeSim: Efficient Simulation of Adhesive Tape Dispensing for Robotic Manipulation"
excerpt: "Adhesive tape dispensing with a reduced roll model, an advancing deformable collar, and flexible released tape. Preprint; under review at ICRA 2027."
collection: portfolio
permalink: /portfolio/tapesim/
display_order: 1
---

**Preprint; under review at ICRA 2027.** [Paper (arXiv v2)](https://arxiv.org/abs/2609.28766v2)

### Authors

**Zhaofeng Luo**, Xinyu Lu, Jaehoon Choi, Zhehuan Chen, Trinity Chung, Xiaowen Qiu, Hugh Nicholas Perkins, Gianna Calderon, Alexis Duburcq, Sanghyun Son, Tsun-Hsuan Wang, Yi-Ling Qiao, Minchen Li

**My role:** Sole first author.

### Overview

Dispensing adhesive tape combines a flexible strip, a moving roll, and interfaces that repeatedly attach and detach. Resolving every wound layer is costly and can suppress roll motion at practical solver tolerances. TapeSim uses a rigid cluster for most wound material and an advancing deformable collar near the unwinding region, preserving a flexible, reattachable released strip.

### Methods and Evaluation

- **Reduced roll representation:** localize deformation while allowing material to leave the roll.
- **Adhesive interfaces:** compare cohesive interfaces with optional releasable bonds.
- **Solver evaluation:** measure roll motion and physics-step cost under fixed tolerances and comparable motion.
- **Robotics evaluation:** use real-motion replays and paired real-to-sim manipulation cases, alongside a teleoperated packaging demonstration.

At **32 turns**, clustering yields **3.2–3.4× mean physics-step speedups at a fixed Newton tolerance** and **4.5–8.4× at comparable roll motion**. These are physics-step measurements, rather than end-to-end application throughput.

### Teleoperated Box Sealing

![Five stages of simulated teleoperated box sealing: close flaps, attach tape, dispense, cut, and press the seal]({{ '/images/tapesim-packaging.png' | relative_url }})

*A simulated teleoperated sequence combines attachment, dispensing, cutting, and sealing in one continuous workflow. Figure from the paper.*

### Resources

[Paper (arXiv v2)](https://arxiv.org/abs/2609.28766v2) · [Publication record]({{ '/publications/tapesim/' | relative_url }})

The paper states that source code will be released.
