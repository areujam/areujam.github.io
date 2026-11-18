---
layout: archive
title: "Research & Engineering"
permalink: /portfolio/
excerpt: "Selected work in distributed machine learning, computational biology, medical AI, and scientific computing."
author_profile: true
---

I build systems that make scientific machine learning more scalable, reproducible, and useful—from distributed training and federated medical imaging to foundation-model data and genomics workflows.

{% include base_path %}

{% assign sorted_projects = site.portfolio | sort: 'date' | reverse %}
{% for post in sorted_projects %}
  {% include archive-single.html %}
{% endfor %}
