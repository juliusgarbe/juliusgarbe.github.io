---
permalink: /teaching/
title: "Teaching"
excerpt: "List of courses I taught."
author_profile: true
redirect_from: 
  - 
---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}