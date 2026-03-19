---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Pusan National University, 2026 (Supervisor: Prof. Joonkyung Jang)
* B.S. in Nano Energy Engineering, Pusan National University, 2019

Work experience
======
* Mar 2026: Research Associate
  * Pusan National University
  * Serving as a Technical Research Personnel (Alternative Military Service)
  * Duties includes: Deriving Machine-Learning Collective Variables (ML-CVs) for rare-event sampling
  * Supervisor: Prof. Joonkyung Jang
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Conferences
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
