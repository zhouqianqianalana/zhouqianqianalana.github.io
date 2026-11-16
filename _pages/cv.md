---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- To offer a PDF download, upload a public CV (without phone/address) to /files/ and uncomment:
[Download my CV (PDF)](/files/CV_QianqianZhou.pdf)
-->

Education
======
* **Ph.D., Petroleum and Geosystems Engineering**, The University of Texas at Austin, 2024 – present
  * Co-advised by Prof. Michael J. Pyrcz and Prof. Maša Prodanović
  * Dissertation: *Multi-Scale Subsurface Characterization: Generative Digital Rocks and Seismic Foundation Model* (proposal exam Nov 2026)
* **M.Eng., Petroleum and Natural Gas Engineering**, China University of Petroleum, Beijing, 2021 – 2024
  * GPA 4.30/5.00, ranked 2/83
* **B.Eng., Petroleum and Natural Gas Engineering**, Southwest Petroleum University, 2017 – 2021
  * GPA 4.03/5.00, ranked 2/308

Research experience
======
* **SynSeis3D and a Synthetic Foundation Model for Seismic Interpretation**, Graduate Research Assistant, UT Austin, Jan 2026 – present
  * Built SynSeis3D, a 7-step rule-based geomodel generator (basement, sequence boundaries, internal architecture, channels, faults, rock physics) with seismic forward simulation
  * Produced 3D seismic volumes with four aligned label channels (faults, channels, basement, intervals), no manual annotation
  * Characterized a 230-volume corpus and compared seismic statistics with the F3 and Parihaka field surveys
  * Trained a multi-task model (frozen SAM ViT-B encoder, shared trunk, 4 heads) on ~12k synthetic slices; basement IoU ≈ 0.97, other tasks 0.55–0.65
* **Latent Rectified Flow for 3D Porous Media Generation**, Graduate Research Assistant, UT Austin, May 2025 – present
  * Developed a two-stage framework: a 3D VAE (128³ → 16×32³ latent) and a rectified-flow ODE generator; about one second per 3D volume on a single GPU
  * Evaluated with porosity, specific surface area, Euler characteristic, voxel-wise Shannon entropy, topological-network PCA, and SSIM
  * Earlier stage: 2D discrete spatial diffusion with Minkowski-functional metrics (AGU 2025)
* **Prediction of 3D Fluid Velocity Fields in Fractured Media (MS-Net)**, warm-up project, UT Austin, 2025
  * Applied MS-Net to predict 3D velocity fields from pySimFrac fracture geometries simulated with LBPM
* **Numerical Simulation of Micro-Proppant Transport over Rough Fractures**, Project Assistant, National Natural Science Foundation of China project, Feb 2022 – 2024
  * Key Python developer of a quantitative fracture-modeling module integrated with CFD–DEM
  * Analyzed migration and settling of conventional vs. micro-sized proppants
* **Proppant Transport by Supercritical CO₂ in Complex Fractures**, Project Leader, Undergraduate thesis, Nov 2020 – May 2021
  * Wrote a program computing CO₂ properties from the Span–Wagner equation of state

Skills
======
* **AI/ML:** Vision foundation models (SAM ViT), multi-task learning, diffusion and rectified-flow models, VAEs, multiscale networks (MS-Net)
* **Programming:** Python (NumPy, SciPy, pandas), PyTorch, PyTorch Lightning
* **HPC / Systems:** TACC, SLURM, performance and memory debugging for large 3D workloads
* **Simulation:** Synthetic geomodeling and seismic forward modeling, CFD–DEM, lattice-Boltzmann (LBPM), pySimFrac

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
