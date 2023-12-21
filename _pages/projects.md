---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
---

{% for project in site.projects reversed %}
  {% include archive-single-project.html%}
{% endfor %}