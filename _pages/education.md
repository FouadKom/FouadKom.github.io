---
layout: archive
title: "Education"
permalink: /education/
author_profile: true
---

{% include base_path %}

{% assign sorted_education = site.education | sort: 'from' | reverse %}

{% for education in sorted_education %}
  {% include archive-single-edu.html education=education %}
{% endfor %}

