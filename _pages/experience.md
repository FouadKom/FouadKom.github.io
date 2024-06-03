---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

{% include base_path %}

{% for certification in cybersecurity_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}
