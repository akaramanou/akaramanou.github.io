---
layout: page
title: Projects
permalink: /projects/
---

## Research Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
  - Status: {{ project.status }}
  - {{ project.description }}
{% endfor %}
