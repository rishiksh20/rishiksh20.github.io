---
layout: archive
title: "Work Experience"
permalink: /work/
author_profile: true
---

{% include base_path %}

**I have ~ 4 years of professional experience in solving real-world problems using AI/ML in the realm of Data Science. Read more below:**

{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}
