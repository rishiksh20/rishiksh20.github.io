---
layout: archive
title: "Work Experience"
permalink: /work/
author_profile: true
---

{% include base_path %}

**I have ~ 4 years of professional experience in solving real-world problems using AI/ML and Data Science techniques.** <br> *I was also awarded with SPOT Awards on 3 occasions during my tenure at Mu Sigma as a Data Scientist.* <br> **Read more below:**

{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}
