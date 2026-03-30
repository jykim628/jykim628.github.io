---
layout: archive
title: "Mechanical Properties of Pressure Sensitive Adhesives"
excerpt: "Investigating the mechanical properties of pressure sensitive adhesives using all-atom MD simulations.<br/><img src='/images/research/Sideproject_01.png' width='100%'>"
status: sideproject
collection: research
author_profile: true
---

{% include base_path %}

Motivation
-----
Pressure-sensitive adhesives (PSAs) are widely used in applications such as medical devices, electronics, and automotive systems, where their performance critically depends on mechanical and rheological properties. Among various PSAs, acrylic-based systems offer tunable properties through copolymer composition. However, understanding how monomer ratios influence macroscopic properties remains challenging due to the lack of molecular-level insight. In this work, I employed all-atom molecular dynamics simulations to investigate how compositional variations affect the structural and mechanical properties of acrylic PSAs, aiming to bridge molecular interactions with macroscopic performance.

<div style="margin-bottom: 20px;"></div>

Methods
-----
All-atom molecular dynamics simulations were performed to model random copolymer systems composed of acrylic acid (AA), 2-ethylhexyl acrylate (2-EHA), and butyl acrylate (BA), with varying monomer ratios. The simulations were carried out using LAMMPS and GROMACS with the OPLS-AA force field. The systems were equilibrated under NPT conditions (300 K, 1 atm) using a Nosé–Hoover thermostat and barostat.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Sideproject_01_Fig1.png" width="50%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 1. Simulation systems with random copolymers.</p>
</div>

Thermophysical and mechanical properties were evaluated through multiple simulation protocols. The glass transition temperature (Tg) was obtained from density and specific volume profiles during cooling simulations from 400 K to 100 K. Viscosity was calculated using the Green–Kubo formalism, while elastic properties, including bulk, Young’s, and shear moduli, were derived from stress–strain relationships based on Lamé constants.

<div style="margin-bottom: 20px;"></div>

Key Results
-----
- The simulated glass transition temperatures (Tg) for selected systems showed good agreement with experimental values, validating the reliability of the MD approach.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Sideproject_01_Fig2.png" width="50%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 2. Density and specific volume as a function of temperature, used to determine the glass transition temperature (Tg).</p>
</div>

- Viscosity predictions were consistent with experimental measurements for some compositions (e.g., K1 and K4), although discrepancies were observed for others, indicating sensitivity to composition and modeling limitations.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Sideproject_01_Fig3.png" width="60%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 3. Comparison of simulated and experimental viscosities across different copolymer compositions.</p>
</div>

- The calculated elastic moduli fell within the typical range of polymer materials, demonstrating that atomistic simulations can capture realistic mechanical behavior.

- Overall, the results highlight that compositional tuning significantly influences PSA properties, and all-atom MD provides a viable framework for predicting structure–property relationships in polymer systems.

<div style="margin-bottom: 50px;"></div>

<div style="margin-top: 40px;">
  <a href="{{ base_path }}/research/">← Back to Research List</a></div>