---
layout: archive
title: "Ceramics"
permalink: /ceramics/
author_profile: true
---

Aside from research, I also do ceramics!

{% include base_path %}

{% for post in site.ceramics reversed %}
  {% include archive-single.html %}
{% endfor %}
