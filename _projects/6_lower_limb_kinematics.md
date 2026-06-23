---
layout: page
title: Kinematics of Lower Limbs
description: Semi-analytical 2D model of knee joint kinematics and forces as a function of morphological parameters (patellar height and trochlear geometry).
img: assets/img/projects/knee_anatomy.png
importance: 2
category: Orthopedic Biomechanics
---

<div style="max-width:55%; margin:0 auto 1.5rem;">
{% include figure.liquid path="assets/img/projects/knee_anatomy.png" alt="Lateral knee X-ray" class="img-fluid rounded z-depth-1" %}
</div>

The kinematics of the knee and the equilibrium forces acting on the joint are intrinsically dependent on the morphology of its components. Specific geometric alterations — whether anatomical variations or consequences of surgical interventions — are associated with increased internal mechanical stresses and a higher incidence of pathological conditions, including anterior knee pain, patellofemoral osteoarthritis, and structural failures.

Clinical evidence links patellofemoral osteoarthritis to extreme values of patellar height, measured by the **Caton-Deschamps index** (ratio of patellar tendon length to patellar articular surface length). These conditions frequently coexist with variations in the femoral trochlear geometry, inducing abnormal lateral patellar displacement and rotation. Trochlear dysplasia (shallow trochlea) is additionally recognized as a determinant factor for articular instability and patellar fractures.

Despite robust clinical evidence, a quantitative understanding of the isolated and combined influence of these morphological parameters on kinematics and joint forces remains limited. This project addresses this gap through a **mathematical modeling approach**:

- Implementing a **2D kinematic model** in the sagittal plane integrating femur, tibia, and patella as rigid bodies connected by joint constraints;
- Developing a **geometric parametrization routine** to systematically simulate variations in the Caton-Deschamps index and trochlear depth;
- **Validating** the model against kinematic and radiographic data from the literature (Hamai et al.) to ensure that the mathematical framework reproduces physiological knee motion;
- Conducting **sensitivity analyses** to isolate the contribution of each geometric parameter to contact forces and extensor mechanism tension under different loading conditions;
- Providing **biomechanical guidance** for the improvement of surgical techniques and prosthesis design for patellofemoral conditions.

The computational platform uses a Newton-Raphson algorithm to solve the kinematic constraint and force equilibrium equations, with control points extracted from radiographic data and articular surfaces represented via splines. Results are intended for publication in biomechanics journals and presentation at ENEBI.

---
<small>Image: lateral X-ray of a normal knee showing femur, tibia, and patella in the sagittal plane. Mikael Häggström, M.D., [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:X-ray_of_a_normal_knee_by_lateral_projection.jpg), CC0 (public domain).</small>
