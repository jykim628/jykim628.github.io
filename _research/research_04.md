---
layout: archive
title: "Machine Learning-Based Collective Variables for Hydrate Simulations"
excerpt: "Deriving machine learning-based collective variables (DeepLDA or SPIB) to accelerate gas hydrate nucleation simulations.<br/><img src='/images/research/Research_04.png' width='100%'>"
status: ongoing
collection: research
author_profile: true
---

{% include base_path %}

Motivation
-----
Gas hydrates are crystalline water structures that can store gas molecules such as methane. While the final structure is thermodynamically determined by guest size, the kinetic pathway toward its formation often involves complex competition among metastable polymorphs.

Capturing these transient structural variations remains challenging, as conventional order parameters typically fail to resolve such degeneracy. Therefore, there is a critical need for robust reaction coordinates that can bridge physical intuition with data-driven insights to elucidate these rare nucleation events.

<div style="margin-bottom: 20px;"></div>

Objectives
-----
To overcome these challenges, I am developing machine learning-based collective variables (ML-CVs) using deep learning and information-theoretic approaches, specifically Deep Linear Discriminant Analysis (DeepLDA) and State Predictive Information Bottleneck (SPIB).

By leveraging existing order parameters as input descriptors, the goal is to derive optimal low-dimensional representations that can resolve subtle structural differences in real time. These ML-CVs will be integrated into enhanced sampling frameworks to reconstruct free energy landscapes and validate both the thermodynamic relevance and kinetic efficiency of the learned variables.

The framework of this work is as follows:
* **Descriptor-driven representation:** Utilizing existing order parameters as input features to overcome the limitations of traditional descriptors.
* **Enhanced sampling integration:** Integrating derived ML-CVs into enhanced sampling frameworks to reconstruct high-fidelity free energy landscapes.
* **Mechanistic validation:** Validating both the thermodynamic and kinetic efficiency of the reaction coordinates to clarify polymorphic selection mechanisms.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Research_04.png" width="80%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 1. Schematic overview of the ML-CV framework. Conventional order parameters are used as input descriptors to train DeepLDA and SPIB models, which learn low-dimensional representations capable of distinguishing polymorphic hydrate states.</p>
</div>

<div style="margin-bottom: 50px;"></div>

<div style="margin-top: 40px;">
  <a href="{{ base_path }}/research/">← Back to Research List</a></div>