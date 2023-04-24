---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

1. Swtiching Devices (SiC, GaN)
2. Passive Componets
3. Sensing Devices 
4. [Converters](/converters)
5. Control Strategies of Microgrids
6. Energy Mangement System (EMS) Design
participation in extremist movements across multiple contexts, gaining insight
into the early stages of radicalization.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}





