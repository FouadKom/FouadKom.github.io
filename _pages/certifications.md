---
layout: archive
title: "Certifications"
permalink: /certifications/
author_profile: true
---

{% include base_path %}

{% for certification in site.certifications reversed %}
  {% include archive-single.html certification=certification %}
{% endfor %}
