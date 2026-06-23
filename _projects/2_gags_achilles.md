---
layout: page
title: GAGs and Achilles Tendon Pathologies
description: Poroelastic modeling of glycosaminoglycan accumulation and elevated intratissue pressure in tendinopathy.
img: assets/img/projects/achilles_tendon.png
importance: 2
category: Computational Biomechanics
---

<div style="max-width:55%; margin:0 auto 1.5rem;">
{% include figure.liquid path="assets/img/projects/achilles_tendon.png" alt="Achilles tendon pain" class="img-fluid rounded z-depth-1" %}
</div>

Tendinopathy — a degenerative condition of the Achilles tendon — is frequently accompanied by changes in the extracellular matrix composition, including the accumulation of glycosaminoglycans (GAGs). This accumulation alters the hydromechanical behavior of the tissue: it impedes fluid exudation under mechanical loading and raises intratissue pressure, a phenomenon possibly associated with the characteristic pain reported by patients.

This project investigates numerically the effect of GAG accumulation on intratissue pressure in tendons. The approach relies on poroelastic models that account for the coupled solid deformation and interstitial fluid flow. A key challenge is that tendons exhibit a highly anisotropic behavior — they are fiber-reinforced soft tissues with a Poisson's ratio often exceeding 0.5 — which is essential to capture fluid exudation under tensile loading (*i.e.*, fluid expelled laterally while the tendon is stretched axially).

The methodological approach includes:

- Formulating **anisotropic poroelastic constitutive equations** that describe the fibrous nature of tendon and its anomalously high Poisson's ratio;
- Implementing the governing equations via the **Finite Element Method**;
- Conducting **comparative simulations** between physiological and pathological GAG concentrations under different loading scenarios (cyclic axial loading, compression);
- Performing **sensitivity and parametric analyses** to quantify the hydromechanical impact of GAG accumulation and calcaneal compression during ankle movement.

The project connects directly to prior experimental and computational work on tendon poromechanics conducted at GRANTE and UNOCHAPECÓ (collaborator: **Prof. Thiago André Carniel**), and draws on existing biphasic simulation infrastructure for model validation and calibration.

---
<small>Image: Achilles tendon region showing localized pain/inflammation at the calcaneal insertion — a hallmark of tendinopathy.</small>
