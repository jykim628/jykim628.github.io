---
layout: archive
title: "Computational Design and Optimization of Visfatin-Derived Therapeutic Peptides"
excerpt: "Designed angiogenic therapeutic peptides derived from visfatin using computational methods, and characterized the protein-peptide interaction using all-atom molecular dynamics simulations.<br/><img src='/images/research/Research_02_2.png' width='100%'>"
status: previous
collection: research
author_profile: true
---

{% include base_path %}

Motivation
-----
Angiogenesis is an essential process for the formation and healing of blood vessels and capillaries, and it plays a critical role in embryogenesis, tissue repair, and organ regeneration. Visfatin, originally identified as pre-B cell colony-enhancing factor (PBEF), has been reported to induce vascular endothelial growth factor (VEGF) production and stimulate angiogenesis, including endothelial cell proliferation and migration. However, its high molecular weight limits its direct therapeutic applicability. To overcome this limitation, we computationally designed visfatin-derived therapeutic peptides that retain the angiogenic activity of visfatin while having a smaller molecular weight.

<div style="margin-bottom: 20px;"></div>

Methods
-----
A computational pipeline was employed to design and characterize visfatin-derived peptides.

First, peptide candidates were generated from the active site domain of Visfatin using an overlapping peptide strategy. Molecular docking simulations (GalaxyPepDock and HADDOCK) were then used to screen peptide binding modes and identify high-affinity candidates.

Selected peptide–Visfatin complexes were further investigated using all-atom molecular dynamics simulations with GROMACS to evaluate structural stability and conformational dynamics. Interaction fingerprint analysis was performed to characterize residue-level interactions.

Finally, computational alanine scanning combined with MM/PBSA calculations was used to identify key residues governing peptide binding and quantify their energetic contributions.

<div style="margin-bottom: 20px;"></div>

Key Results
-----
**Peptide Design and Functional Validation**
- A total of 114 peptides were generated, and 9 candidates with high binding affinity were identified through docking simulations.
- In vitro assays revealed that two peptides exhibited superior angiogenic activity compared to visfatin.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Research_02_Fig1.png" width="60%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 1. In vitro validation of angiogenic activity for visfatin-derived peptides.</p>
</div>

**Structural Stability and Binding Behavior**
- MD simulations showed that both peptides form stable complexes with Visfatin, maintaining consistent conformations throughout the simulation.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Research_02_Fig2.png" width="75%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 2. Structural stability and conformational dynamics of peptide–Visfatin complexes from MD simulations.</p>
</div>

**Interaction Mechanism**
- Interaction fingerprint analysis revealed persistent residue-level interactions, indicating stable binding interfaces.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Research_02_Fig3.png" width="50%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 3. Interaction fingerprint analysis showing residue-level interactions between peptides and Visfatin.</p>
</div>

- Computational alanine scanning identified key residues responsible for binding stability and energetic contributions.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Research_02_Fig4.png" width="60%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 4. Identification of key residues using computational alanine scanning and binding free energy analysis.</p>
</div>


<div style="margin-bottom: 50px;"></div>

<div style="margin-top: 40px;">
  <a href="{{ base_path }}/research/">← Back to Research List</a></div>