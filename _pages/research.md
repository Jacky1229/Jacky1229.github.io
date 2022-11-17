---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}
This is research page.
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
