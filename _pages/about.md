---
permalink: /
title: "About Me"
description: "Zhaofeng Luo is a Computer Science PhD student at Carnegie Mellon University researching GPU physics simulation, contact mechanics, and deformable objects for robotics."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello! I'm **Zhaofeng Luo (罗兆丰)**, a PhD student in the School of Computer Science at Carnegie Mellon University, advised by Prof. Minchen Li.

I develop **robust and efficient physics-based simulation methods**, with a focus on **GPU computation, contact, and deformable materials**. My work connects numerical methods and interactive systems: from accelerating contact-rich simulation to modeling adhesive tape for robotic manipulation and elastoplastic materials for hands-on VR modeling.

[CV (PDF)]({{ '/files/CV.pdf' | relative_url }}) · [Publications]({{ '/publications/' | relative_url }}) · [GitHub](https://github.com/Roushelfy) · [Email](mailto:zhaofen2@andrew.cmu.edu)

## Selected Research

<article class="research-feature research-feature--spotlight">
  <div class="research-feature__text">
    <p class="research-feature__meta">2026 · Sole first author · Preprint · Under review at ICRA 2027</p>
    <h3><a href="{{ '/portfolio/tapesim/' | relative_url }}">TapeSim: Adhesive Tape for Robotic Manipulation</a></h3>
    <p>TapeSim models a dispensing roll with a rigid cluster, an advancing deformable collar, and a flexible, reattachable strip. The simulator supports attachment, dispensing, cutting, and sealing in a continuous teleoperated box-sealing workflow.</p>
    <p>At 32 turns, clustering gives <strong>4.5–8.4× faster mean physics steps at comparable roll motion</strong>. Evaluation includes real-motion replays and paired real-to-sim manipulation cases.</p>
    <a href="{{ '/portfolio/tapesim/' | relative_url }}"><img src="{{ '/images/tapesim-packaging.png' | relative_url }}" alt="Five stages of simulated teleoperated box sealing: close flaps, attach tape, dispense, cut, and press the seal" loading="lazy"></a>
    <p class="research-feature__links"><a href="{{ '/portfolio/tapesim/' | relative_url }}">Overview</a> · <a href="https://arxiv.org/abs/2609.28766v2">Paper</a></p>
  </div>
</article>

<article class="research-feature">
  <div class="research-feature__text">
    <p class="research-feature__meta">SIGGRAPH 2026 · Conference Papers</p>
    <h3><a href="{{ '/portfolio/portfolio-8/' | relative_url }}">AGIPC: Adaptive In-Solve Algebraic Coarsening for GPU IPC</a></h3>
    <p>Adaptive coarsening inside the Newton solve reduces computational cost without remeshing, with GPU-parallel assembly and contact handling.</p>
    <p class="research-feature__links"><a href="{{ '/portfolio/portfolio-8/' | relative_url }}">Overview</a> · <a href="https://arxiv.org/abs/2605.04773">Paper</a></p>
  </div>
  <a class="research-feature__image" href="{{ '/portfolio/portfolio-8/' | relative_url }}"><img src="{{ '/images/agipc-teaser-1.jpg' | relative_url }}" alt="Simulation examples from AGIPC" loading="lazy"></a>
</article>

<article class="research-feature">
  <div class="research-feature__text">
    <p class="research-feature__meta">SIGGRAPH 2026 · ACM Transactions on Graphics</p>
    <h3><a href="{{ '/portfolio/portfolio-4/' | relative_url }}">Penetration-Free Elastodynamics without Barriers</a></h3>
    <p>An augmented Lagrangian approach to contact-rich elastic simulation, addressing the conditioning and collision-detection challenges of barrier-based methods.</p>
    <p class="research-feature__links"><a href="{{ '/portfolio/portfolio-4/' | relative_url }}">Overview</a> · <a href="https://simulation-intelligence.github.io/barrier-free/">Project</a> · <a href="https://arxiv.org/abs/2512.12151">Paper</a></p>
  </div>
  <a class="research-feature__image" href="{{ '/portfolio/portfolio-4/' | relative_url }}"><img src="{{ '/images/barrier_free_teaser.jpg' | relative_url }}" alt="Contact-rich deformable simulation from Barrier-Free Elastodynamics" loading="lazy"></a>
</article>

<article class="research-feature">
  <div class="research-feature__text">
    <p class="research-feature__meta">2026 · Preprint</p>
    <h3><a href="{{ '/portfolio/schwarz-mpm/' | relative_url }}">Overlapping Schwarz Space-Time Refinement for MPM</a></h3>
    <p>Local spatial refinement and temporal sub-cycling concentrate computation where deformation and contact require it, while preserving standard MPM discretizations within each subdomain.</p>
    <p class="research-feature__links"><a href="{{ '/portfolio/schwarz-mpm/' | relative_url }}">Overview</a> · <a href="https://arxiv.org/abs/2605.09097">Paper</a></p>
  </div>
</article>

<article class="research-feature">
  <div class="research-feature__text">
    <p class="research-feature__meta">SIGGRAPH 2025 · ACM Transactions on Graphics</p>
    <h3><a href="{{ '/portfolio/portfolio-5/' | relative_url }}">VR-Doh: Hands-on 3D Modeling in Virtual Reality</a></h3>
    <p>An interactive modeling system that combines MPM-based elastoplastic simulation and natural hand interaction. I designed, implemented, and tested the full system. Selected as a <strong>Top 10 Technical Papers Fast Forward</strong>.</p>
    <p class="research-feature__links"><a href="{{ '/portfolio/portfolio-5/' | relative_url }}">Overview</a> · <a href="https://simulation-intelligence.github.io/VR-Doh/">Project and paper</a></p>
  </div>
  <a class="research-feature__image" href="{{ '/portfolio/portfolio-5/' | relative_url }}"><img src="{{ '/images/VR-Doh-Teaser.jpg' | relative_url }}" alt="Hands-on modeling examples from VR-Doh" loading="lazy"></a>
</article>

## Open-Source and Teaching Resources

- **[Libuipc]({{ '/portfolio/portfolio-3/' | relative_url }})** — contributions to a C++20 framework for GPU incremental potential contact and coupled rigid and deformable simulation. [Project](https://spirimirror.github.io/libuipc-web/)
- **[GPU solid simulation tutorial]({{ '/portfolio/portfolio-7/' | relative_url }})** — tutorial code and course material for the open-source *Physics-based Simulation* book. [Code](https://github.com/phys-sim-book/solid-sim-tutorial-gpu) · [Chapter](https://phys-sim-book.github.io/lec4.6-gpu_accel.html)
- **Teaching assistant, CMU 15-369/769** — *Numerical Methods: Foundations, ML, and Visual Computing*, Fall 2026. [Course](https://www.cs.cmu.edu/~15369-f26/)

## Outside Research

I enjoy tennis. At Peking University, I served as captain of the School of EECS tennis team and president of the Student Tennis Association, organizing tournaments and classes.
