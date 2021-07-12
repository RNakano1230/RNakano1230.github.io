---
permalink: /research/
title: "Research"
author_profile: true
---

I aim to solve technologically and scientifically challenging problems by
exploring various engineering techniques.

## Current Projects
{% include base_path %}
{% assign ordered_pages = site.research | sort:"order_number" %}
{% for post in ordered_pages %}
    {% include archive-research.html %}
{% endfor %}

## Past Projects

### Development of a 3D-printed electric propulsion device for small satellites

### Marsbee project
