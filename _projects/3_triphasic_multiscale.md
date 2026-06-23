---
layout: page
title: Multiscale Triphasic Modeling and Ion Transport
description: Second-order computational homogenization for triphasic (solid–fluid–ions) porous media under large deformations.
img: assets/img/projects/gag_proteoglycan_structure.jpg
importance: 3
category: Computational Biomechanics
---

<div style="max-width:55%; margin:0 auto 1.5rem;">
{% include figure.liquid path="assets/img/projects/gag_proteoglycan_structure.jpg" alt="Aggrecan and GAG structure" class="img-fluid rounded z-depth-1" %}
</div>

Soft biological tissues such as the arterial wall and tendons are densely populated by glycosaminoglycans (GAGs), which carry fixed negative charges. These charges interact with the ions present in the interstitial fluid, generating electrochemical potentials that govern the stress state and swelling behavior of the tissue. This chemo-mechanical coupling is at the heart of phenomena such as Donnan osmotic swelling and ion-driven tissue remodeling.

The classical biphasic (solid–fluid) representation is insufficient to describe these complex osmotic phenomena and solute transport, which are fundamental to the homeostasis and pathogenesis of soft tissues. This project extends our existing second-order poromechanical homogenization framework to a **triphasic formulation**, integrating ion transport and chemo-electro-mechanical coupling under large deformations.

The computational framework is based on the **Method of Multiscale Virtual Power (MMVP)**, and the development plan includes:

- Formulating **triphasic mass and momentum balance equations** at the RVE scale, incorporating solvent flux and ionic diffusion via Nernst-Planck equations;
- Developing **insertion and homogenization operators** that guarantee variational consistency of ionic concentrations and chemical potentials across macro and meso scales;
- Implementing the framework numerically via the **Finite Element Method** (FEniCSx), using mixed formulations to handle incompressibility of constituents and potential gradients;
- Validating the framework against **Direct Numerical Simulations (DNS)** of heterogeneous domains, verifying scale transfer accuracy for concentration gradients and membrane potentials;
- Applying the model to quantify the **Donnan osmotic swelling** induced by pathological GAG accumulation and its effect on microscale stress redistribution.

This project is developed in close collaboration with **Prof. Pablo Javier Blanco** (LNCC — Laboratório Nacional de Computação Científica), leveraging FE² multiscale infrastructure and access to the Santos Dumont supercomputer for large-scale simulations.

---
<small>Image: schematic of aggrecan structure (A) showing protein core with keratan sulfate and chondroitin sulfate GAG chains, and proteoglycan aggregates bound to hyaluronan (B) — the fixed-charge bearing components that drive Donnan osmotic pressure in the triphasic model. From: Carballo et al., *Int. J. Mol. Sci.* 24(13):10824, 2023 ([PMC10341989](https://pmc.ncbi.nlm.nih.gov/articles/PMC10341989/)), CC BY 4.0.</small>
