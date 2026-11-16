---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm **Qianqian Zhou**, a Ph.D. student in the [Hildebrand Department of Petroleum and Geosystems Engineering](https://pge.utexas.edu/) at **The University of Texas at Austin**, co-advised by [Prof. Michael J. Pyrcz](https://michaelpyrcz.com/) and [Prof. Maša Prodanović](https://sites.google.com/utexas.edu/masha/home).

My dissertation, *Multi-Scale Subsurface Characterization: Generative Digital Rocks and a Seismic Foundation Model*, asks whether **synthetic data can stand in for scarce, costly subsurface data** at both the pore and the basin scale, provided it is representative enough. I build generators, measure how representative their output is, and train models that learn from it:

- **Generative digital rocks.** A latent rectified-flow model (3D VAE + rectified flow) generates realistic 3D pore structures in about a second each on a single GPU. I evaluate them with porosity, topology, entropy-based uncertainty, and diversity metrics.
- **SynSeis3D.** An open, geology-aware engine that forward-models 3D seismic volumes with perfectly aligned labels for faults, channels, basement, and intervals.
- **A seismic foundation model.** Multi-task interpretation learned from synthetic data on vision foundation-model encoders such as SAM ViT, with parameter-efficient adaptation and transfer to field surveys.

I train and run these models at scale on [TACC](https://tacc.utexas.edu/) supercomputers with PyTorch and PyTorch Lightning. See [Research](/research/) for details.

Before UT, I earned my M.Eng. at **China University of Petroleum, Beijing** (ranked 2/83) and my B.Eng. at **Southwest Petroleum University** (ranked 2/308), where I worked on CFD–DEM simulation of proppant transport in rough fractures.

News
------
- **Nov 2026** · PhD proposal exam: *Multi-Scale Subsurface Characterization: Generative Digital Rocks and Seismic Foundation Model* (Nov 19).
- **2026** · *SynSeis3D* paper submitted to *Computers & Geosciences*.
- **Oct 2026** · Presented *Toward a Synthetic Foundation Model for Seismic Interpretation* at the S&P Global Energy Update Meeting.
- **May 2026** · Presented *Latent Diffusion with Rectified Flow for 3D Porous Media* at the DIRECT Consortium 7th Annual Meeting.
- **Dec 2025** · Oral presentation at **AGU 2025** in New Orleans on discrete spatial diffusion for rock image generation.
- **Aug 2025** · Poster at **IMAGE '25** in Houston on predicting 3D flow fields in fractures with MS-Net.
- **Aug 2025** · Teaching assistant for PGE 311, Numerical Methods & Programming.
- **Aug 2024** · Joined UT Austin as a Ph.D. student.

Research interests
------
Multi-scale subsurface characterization · Foundation models for geoscience · Synthetic data · Seismic interpretation · Generative models (diffusion, rectified flow, VAEs) · Digital rock physics · Porous media · Uncertainty quantification · Scientific computing on HPC
