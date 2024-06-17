---
layout: archive
title: ""
permalink: /certifications/
author_profile: true
---

{% include base_path %}

<h1>Certifications</h1>

<h2>Cybersecurity</h2>
{% assign cybersecurity_certs = site.certifications | where: "category", "cybersecurity" | reverse %}
{% for certification in cybersecurity_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}

***

<h2>Machine Learning</h2>
{% assign ML_certs = site.certifications | where: "category", "ML" | reverse %}
{% for certification in ML_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}

***

<h2>Data Analysis/Engineering</h2>
{% assign data_certs = site.certifications | where: "category", "dataEngineering" | reverse %}
{% for certification in data_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}

***

<h2>Data Visualization</h2>
{% assign data_certs = site.certifications | where: "category", "dataVisualization" | reverse %}
{% for certification in data_certs %}
  {% include archive-single-certs.html certification=certification %}
{% endfor %}
