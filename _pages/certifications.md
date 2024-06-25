---
layout: archive
title: ""
permalink: /certifications/
author_profile: true
---

{% include base_path %}

<h1>Cybersecurity</h1>
{% assign cyber_certs = site.certifications | where: "category", "cybersecurity" | reverse %}
{% for certification in cyber_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}

***

<h1>Data Analysis/Engineering</h1>
{% assign data_certs = site.certifications | where: "category", "dataEngineering" | reverse %}
{% for certification in data_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}

***

<h1>Machine Learning</h1>
{% assign ML_certs = site.certifications | where: "category", "ML" | reverse %}
{% for certification in ML_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}

***

<h2>Data Visualization</h2>
{% assign data_certs = site.certifications | where: "category", "dataVisualization" | reverse %}
{% for certification in data_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}
