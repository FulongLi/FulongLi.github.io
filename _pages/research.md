---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

Microgrid is my life:
---
My academic research falls into two main areas：

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

---
1. Switching Devices (SiC, GaN)
2. Passive Componets
3. Sensing Devices
4. Converters
5. Control Strategies of Microgrids
6. Energy Mangement System (EMS) Design
