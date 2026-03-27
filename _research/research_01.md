---
layout: archive
title: "Extracting the Size Distribution of Gold Nanoparticles from UV-Visible Spectrum"
excerpt: "Proposed an ANN model trained on Mie theory to extract particle size distributions from UV-visible spectra, providing a robust alternative to conventional DLS methods.<br/><img src='/images/research/Research_01.png' width='100%'>"
status: previous
collection: research
author_profile: true
---

{% include base_path %}

Motivation & Objective
-----
Metallic nanoparticles (NPs) are widely used in catalysis, biomedicine, and energy applications, where their properties strongly depend on particle size distribution (PSD). Accurate characterization of PSD is therefore essential. While various experimental methods exist for PSD characterization, they often suffer from limitations such as high cost, time consumption, and sample damage. The objective of this study is to develop an alternative, non-destructive method for extracting PSD from experimental observables. In this work, I developed an artificial neural network (ANN) model to extract PSD from UV-visible spectra.

<div style="margin-bottom: 20px;"></div>

Methods
-----
To establish a mapping between UV-visible spectra and particle size distribution (PSD), I generated a large synthetic dataset using Mie theory. The extinction spectra were computed for gold nanoparticles with diverse size distributions, enabling systematic coverage of physically relevant cases.

Based on this dataset, I developed an artificial neural network (ANN) model that takes a UV-visible spectrum as input and predicts the corresponding PSD. The model consists of multiple fully connected layers and was trained using backpropagation with regularization techniques to prevent overfitting.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Research_01_Fig1.png" width="50%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 1. Architecture of the ANN model.</p>
</div>

<div style="margin-bottom: 20px;"></div>

Key Results
-----
- The ANN model successfully learned the relationship between UV-visible spectra and PSD, achieving consistent performance across training and test datasets without signs of overfitting.

- When applied to experimental data, the model showed strong agreement with measured particle sizes, achieving a high correlation (R² ≈ 0.93).

- The model demonstrated particularly reliable predictions for nanoparticles larger than ~45 nm, while reduced accuracy at smaller sizes was attributed to limited spectral variation in this regime.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Research_01_Fig2.png" width="40%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 2. Comparison of predicted and experimental mean diameters.</p>
</div>

<div style="margin-bottom: 50px;"></div>

<div style="margin-top: 40px;">
  <a href="{{ base_path }}/research/">← Back to Research List</a></div>

