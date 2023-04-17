---
layout: archive
title: "Ceramics"
permalink: /ceramics/
author_profile: true
---

Aside from research, I also do ceramics!
![ceramics-1](http://alexandralalor.github.io/images/ceramics/ceramics-1.jpg)


-----
{% include base_path %}

{% for post in site.ceramics reversed %}
  {% include archive-single.html %}
{% endfor %}

{% for image in site.static_files %}
    {% if image.path contains 'images/ceramics' %}
        <img src="https://alexandralalor.github.io{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}

<p style="line-height: 100px;">
<img src="images/ceramics/ceramis-1.jpg"><br>
<img src="images/ceramics/ceramis-2.jpg"><br>
</p>
