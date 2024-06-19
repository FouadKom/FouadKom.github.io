---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

{% include base_path %}

{% assign sorted_experiences = site.experience | sort: 'from' | reverse %}

{% for experience in sorted_experiences %}
  {% include archive-single-exp.html %}
  ***
{% endfor %}

