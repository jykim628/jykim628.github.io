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
* **Ph.D.**, Pusan National University, Korea. **2026**
  * (Advisor: Prof. Joonkyung Jang)
* **B.S.**, Pusan National University, Korea. **2019**

Work experience
======
* **Research Associate**, Pusan National University, Korea. **Mar. 2026 -**
  * Serving as a Technical Research Personnel (Alternative Military Service)
  * Deriving machine learning collective variables (ML-CVs) for rare-event sampling
  * Advisor: Prof. Joonkyung Jang
  
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
