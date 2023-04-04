---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Lalor, A.R.**, Law, D.J., Breshears, D.D., Falk, D.A., Field, J.P., Loehman, R.A., Triepki, F.J., Barron-Gafford, G.A., 2023. Mortality Thresholds of Juvenile Trees to Drought and Heatwaves: Implications for Forest Regeneration across a Landscape Gradient. *Frontiers in Forests and Global Change*, 2, p.89.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
