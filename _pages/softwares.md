---
layout: archive
title: "Softwares"
permalink: /softwares/
author_profile: true
---

{% include base_path %}


{% for post in site.softwares reversed %}
  {% include archive-single.html %}
{% endfor %}
