---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Ongoing Works
---
{% for post in site.research %}
  {% if post.status == "ongoing" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<div style="margin-bottom: 50px;"></div>

## Previous Research
---
{% for post in site.research %}
  {% if post.status == "previous" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
