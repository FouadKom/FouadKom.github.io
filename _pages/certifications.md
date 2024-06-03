---
layout: archive
title: ""
permalink: /certifications/
author_profile: true
---

{% include base_path %}

<h1>Cybersecurity</h1>
{% assign cybersecurity_certs = site.certifications | where: "category", "cybersecurity" %}
{% for certification in cybersecurity_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}

***

<h1>Machine Learning</h1>
{% assign ML_certs = site.certifications | where: "category", "ML" %}
{% for certification in ML_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}

***

<h1>Data Analysis/Engineering</h1>
{% assign data_certs = site.certifications | where: "category", "data" %}
{% for certification in data_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}
