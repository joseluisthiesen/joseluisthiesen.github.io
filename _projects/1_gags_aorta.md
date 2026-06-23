---
layout: page
title: GAGs and Aortic Dissection
description: Multiscale poroelastic modeling of glycosaminoglycan-induced osmotic swelling and delamination risk in the aortic wall.
img: assets/img/projects/aorta_microstructure.jpg
importance: 1
category: Computational Biomechanics
---

<div style="max-width:55%; margin:0 auto 1.5rem;">
{% include figure.liquid path="assets/img/projects/aorta_microstructure.png" alt="Aortic dissection layers" class="img-fluid rounded z-depth-1" %}
</div>

Aortic dissection is a life-threatening condition in which a tear propagates between the layers of the arterial wall. A key but underexplored trigger is the transmural accumulation of glycosaminoglycans (GAGs) in the tunica media — a pathological condition known as T-MEMA (Transverse Medial Elastin Mucoid Accumulation). GAGs carry fixed negative charges that attract counter-ions from the interstitial fluid, generating Donnan osmotic swelling pressure. When concentrated in specific transmural locations, this swelling creates radial stress concentrations that are hypothesized to initiate delamination.

This project develops a multiscale computational framework that couples large-deformation poromechanics with Donnan osmotic swelling to quantify how GAG localization drives radial stresses and failure in the aortic wall. The modeling approach integrates:

- A **poroelastic/triphasic formulation** governing fluid flow and osmotic pressure at the microscale (interlamellar RVEs);
- An **anisotropic hyperelastic failure model** incorporating the mechanics of radial elastin struts (*radial elastin struts*) as failure-critical elements;
- A **second-order multiscale computational homogenization** framework that transfers kinematic and osmotic variables between the macro (continuous arterial wall) and micro scales;
- **Biomechanical simulations** under realistic physiological loading (cyclic blood pressure) to assess how GAG-induced swelling alters macroscopic stress fields;
- **Parametric studies** to quantify how transmural localization of T-MEMA aggravates local stresses and predisposes structural failure.

This work builds on prior contributions to second-order poromechanical homogenization and extends them to include chemo-mechanical coupling relevant to arterial tissue pathology. It is conducted in collaboration with **Prof. Claudio Garcia Herrera** (Universidad Adolfo Ibáñez, Chile), who provides experimental expertise in arterial tissue characterization and delamination testing (peeling and fluid injection modes).

---
<small>Image: illustration of aortic dissection showing the three-layer wall structure (intima, media, adventitia) and the dissection tear. © 2019 [Society of Thoracic Surgeons (STS)](https://www.sts.org).</small>
