---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a fourth-yearPh.D. student in Computer Engineering at the University of Illinois Urbana-Champaign, advised by Prof. [Sayan Mitra](https://mitras.ece.illinois.edu/index.html). I received my B.Eng. in Automation from Tsinghua University, with a minor in Data Science.

My research focuses on **formal verification, trustworthy autonomy, neural rendering, 3D reconstruction, and controller synthesis**, with the goal of building reliable perception-control systems with formal guarantees.

## News

- **2025:** Our paper **Abstract Rendering: Certified Rendering Under 3D Semantic Uncertainty** was accepted as a Spotlight paper at NeurIPS 2025.
- **2025:** Our paper **Reachability for Nonsmooth Systems with Lexicographic Jacobians** was accepted to TACAS 2025.
- **2025:** Our paper **Lyapunov Perception Contracts for Operating Design Domains** was accepted to L4DC 2025.

## Selected Publications

### Abstract Rendering: Certified Rendering Under 3D Semantic Uncertainty

**Chenxi Ji\***, Yangge Li\*, Xiangru Zhong\*, Huan Zhang, and Sayan Mitra.  
**NeurIPS 2025 Spotlight.**

<img src="/images/absrend_result.png" alt="Abstract Rendering result" style="width: 85%; min-width: 300px; border-radius: 6px; margin-top: 8px; margin-bottom: 12px;">

Abstract Rendering computes provable bounds on all images rendered under continuous camera-pose and scene variations. It propagates 3D uncertainty through Gaussian Splatting and NeRF, enabling certification of downstream vision models such as classifiers, detectors, and pose estimators. This supports formal reasoning beyond traditional pixel-level noise models.

[Paper](/files/abstract_rendering_neurips2025.pdf) / [Poster](/files/absrend_poster_neurips25.pdf) / [Project Page](https://illinoisreliableautonomygroup.github.io/Abstract-Rendering-Webpage/) / [Code](https://github.com/IllinoisReliableAutonomyGroup/Abstract-Rendering) / [BibTeX](/files/bibtex/abstract_rendering_neurips2025.txt)

---

### Lyapunov Perception Contracts for Operating Design Domains

Yangge Li, **Chenxi Ji**, Jai Anchalia, Yixuan Jia, Benjamin C. Yang, Daniel Zhuang, and Sayan Mitra.  
**L4DC 2025.**

<div style="display: flex; gap: 16px; align-items: center; flex-wrap: wrap; margin-top: 8px; margin-bottom: 12px;">
  <img src="/images/contract.png" alt="Lyapunov Perception Contract" style="height: 220px; width: auto; max-width: 100%; border-radius: 6px;">
  <img src="/images/reach_set.png" alt="Reach set for Lyapunov Perception Contract" style="height: 220px; width: auto; max-width: 100%; border-radius: 6px;">
</div>

Lyapunov Perception Contracts provide specifications for DNN-based state estimators that guarantee closed-loop stability. The framework connects image rendering, environmental parameters, perception uncertainty, and controller dynamics. It can synthesize operating design domains for visual controllers under lighting, weather, and other environmental variations.

[Paper](/files/lyapunov_perception_contracts_l4dc2025.pdf) / [Poster](/files/lyp_perception_contract_poster_l4dc25.pdf) / [BibTeX](/files/bibtex/lyapunov_perception_contracts_l4dc2025.txt)

---

### Reachability for Nonsmooth Systems with Lexicographic Jacobians

**Chenxi Ji**, Huan Zhang, and Sayan Mitra.  
**TACAS 2025.**

<img src="/images/nonsmooth_reach.png" alt="Nonsmooth reachability" style="width: 85%; min-width: 300px; border-radius: 6px; margin-top: 8px; margin-bottom: 12px;">

This work develops reachability analysis for nonsmooth dynamical systems using lexicographic Jacobians. The method avoids hybridizing nonsmooth systems into separate smooth modes and improves reachset accuracy across mode boundaries. It also supports verification of ReLU neural ODEs and other nonsmooth models.

[Paper](/files/nonsmooth_reachability_tacas2025.pdf) / [Poster](/files/nonsmooth_reach_poster_tacas25.pdf) / [BibTeX](/files/bibtex/nonsmooth_reachability_tacas2025.txt)
