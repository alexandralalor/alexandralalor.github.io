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


---
title: "Portfolio item number 1"
excerpt: "1<br/><img src='images/ceramics/ceramics-1.jpg'>"
collection: ceramics
---

This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML. 
