---
layout: archive
title: "Work Experience"
permalink: /work/
author_profile: true
---

{% include base_path %}

**I have ~ 4 years of professional experience in solving real-world problems using AI/ML and Data Science techniques in Retail, Telecom, and Healthcare domains.** <br> *I was awarded with SPOT Awards on 3 occasions during my tenure at Mu Sigma as a Data Scientist for exceeding project goals, delivering exceptional results and designing optimal solutions..* <br> **For a detailed description of my professional journey, read below:**

{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}
