---
layout: archive
title: "Inhibitory Effect of Amylose on the Growth of Hydrate"
excerpt: "Investigated the inhibitory mechanism of amylose on methane hydrate growth using 1-μs all-atom molecular dynamics simulation, revealing molecular-level insights into hydrate inhibition.<br/><img src='/images/research/Research_02.png' width='100%'>"
status: previous
collection: research
author_profile: true
---

{% include base_path %}

Motivation
-----
Gas hydrates are crystalline water structures that can store gas molecules such as methane. While they are considered potential energy resources, they also pose serious challenges by causing blockages in pipelines. Biodegradable polymers such as starch have been proposed as environmentally friendly hydrate inhibitors. However, whether and how starch regulates hydrate formation remains unclear at the molecular level. In this work, I used all-atom molecular dynamics simulations to investigate the inhibitory role of amylose, a major component of starch, and to uncover the underlying molecular mechanisms.

<div style="margin-bottom: 20px;"></div>

Methods
-----
To investigate hydrate growth, I performed all-atom molecular dynamics simulations of methane hydrate formation in the presence of amylose and its modified form (OMet-amylose). A hydrate seed (sI structure) was introduced to model growth, and simulations were carried out under hydrate-forming conditions (250 K, 100 bar) for up to 1 μs. The system was analyzed using structural and dynamical metrics, including hydrate cage counting, order parameters (F4), mean square displacement (MSD), and hydrogen bonding analysis. By comparing amylose and OMet-amylose, I isolated the effects of hydrogen bonding and steric interactions on hydrate growth.

<div style="margin-bottom: 20px;"></div>

Key Results
-----
- Amylose significantly inhibited hydrate growth, whereas OMet-amylose showed weaker inhibition despite its larger size.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Research_02_Fig1.png" width="75%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 1. Growth of methane hydrate in the absence/presence of additive.</p>
</div>

- The inhibition mechanism was identified as twofold: (1) hydrogen bonding between amylose and the hydrate surface, and (2) steric hindrance preventing water molecules from accessing the hydrate seed.

- Hydrogen bonding played a dominant role: amylose formed stable H-bond networks and ring-like structures with water, disrupting hydrate cage formation.

<div style="text-align: center;">
  <img src="{{ base_path }}/images/research/Research_02_Fig2.png" width="35%">
  <p style="font-size: 0.85em; margin-top: 5px">Figure 2. Ring structures hampering the growth of a hydrate with the amylose molecule.</p>
</div>

- In contrast, OMet-amylose formed fewer hydrogen bonds and did not induce such structural disruptions, leading to weaker inhibition.

- Structural (cage count, F4) and dynamical (MSD) analyses consistently showed that amylose most effectively suppressed hydrate growth.

<div style="margin-bottom: 50px;"></div>

<div style="margin-top: 40px;">
  <a href="{{ base_path }}/research/">← Back to Research List</a></div>