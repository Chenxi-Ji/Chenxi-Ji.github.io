---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. student in Computer Engineering at the University of Illinois Urbana-Champaign, advised by Prof. Sayan Mitra. I received my B.Eng. in Automation from Tsinghua University, with a minor in Data Science.

My research focuses on **formal verification, trustworthy autonomy, neural rendering, 3D reconstruction, and controller synthesis**, with the goal of building reliable perception-control systems with formal guarantees.

## News

- **2025:** Our paper **Abstract Rendering: Certifying Rendering under 3D Semantic Uncertainty** was accepted as a Spotlight paper at NeurIPS 2025.
- **2025:** Our paper **Reachability for Nonsmooth Systems with Lexicographic Jacobian** was accepted to TACAS 2025.
- **2025:** Our papers on perception contracts and vision-based autonomy were accepted to L4DC 2025 and ICCPS 2025.

## Selected Publications

### Abstract Rendering: Certifying Rendering under 3D Semantic Uncertainty

<div style="display: flex; gap: 14px; flex-wrap: wrap; margin-bottom: 12px;">
  <img src="/images/absrend_result.png" alt="Abstract Rendering result" style="width: 46%; min-width: 260px; border-radius: 6px;">
  <img src="/images/classification_result.png" alt="Classification result" style="width: 46%; min-width: 260px; border-radius: 6px;">
</div>

**Chenxi Ji\***, Yangge Li\*, Xiangru Zhong\*, Huan Zhang, Sayan Mitra  
**NeurIPS 2025 Spotlight**

We certify learning-based rendering algorithms under 3D semantic uncertainty. The method propagates uncertainty through neural rendering models such as Gaussian Splatting and NeRF. The results support reliable perception and visual autonomy under uncertain scene or camera conditions.

[Paper](/files/abstract_rendering.pdf) / [Code](https://github.com/IllinoisReliableAutonomyGroup/Abstract-Rendering) / [Project Page](https://illinoisreliableautonomygroup.github.io/Abstract-Rendering-Webpage/)

---

### Perception Contracts for Vision-based Autonomy

<div style="margin-bottom: 12px;">
  <img src="/images/env_params.png" alt="Perception contract environment parameters" style="width: 70%; min-width: 300px; border-radius: 6px;">
</div>

**Chenxi Ji**, Yangge Li, Jai Anchalia, Joshua Neighbor, Prashin S. Sharma, Sayan Mitra  
**ACM TCPS submission, 2026**

We study perception contracts for reasoning about reliability in vision-based autonomy. The framework connects perception uncertainty with downstream closed-loop stability and safety analysis. It provides a principled way to certify autonomy systems under operating-domain variations.

[Paper](/files/perception_contract.pdf)

---

### Reachability for Nonsmooth Systems with Lexicographic Jacobian

<div style="margin-bottom: 12px;">
  <img src="/images/nonsmooth_reach.png" alt="Nonsmooth reachability" style="width: 70%; min-width: 300px; border-radius: 6px;">
</div>

**Chenxi Ji**, Huan Zhang, Sayan Mitra  
**TACAS 2025**

We develop reachability analysis methods for nonsmooth dynamical systems. The approach uses lexicographic Jacobians to reason about systems where standard differentiability assumptions fail. It enables formal verification of broader classes of neural and hybrid dynamical systems.

[Paper](/files/nonsmooth_reachability.pdf)
