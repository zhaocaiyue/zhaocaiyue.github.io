---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


Member of the [Smart Mobility Lab at HKU](https://sites.google.com/view/kejintao/home), Principal Investigator: Dr. Jintao Ke.

{% include base_path %}

Working Paper
======
{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

Projects
======
{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}