---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

{% include base_path %}

{% for post in site.experience reversed %}
  {% include archive-single-exp.html experience=post %}
{% endfor %}