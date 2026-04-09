---
layout: page
title: Papers
permalink: /papers/
---

## Research Papers

{% for paper in site.papers %}
- [{{ paper.title }}]({{ paper.url }}) ({{ paper.year }})
  - Authors: {{ paper.authors }}
  - Published in: {{ paper.venue }}
{% endfor %}
