---
permalink: /research/
title: "Research"
author_profile: true
---

Through my research, I aim to solve technologically and
scientifically challenging problems. I explore various engineering techniques
to further advance our knowledge and understanding of space.

## Current Projects
{% include base_path %}
{% assign ordered_pages = site.research | sort:"order_number" %}
{% for post in ordered_pages %}
    {% include archive-research.html %}
{% endfor %}

## Past Projects

### Development of a 3D-printed electric propulsion device for small satellites

### Marsbee project
