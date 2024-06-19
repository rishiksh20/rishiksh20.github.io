---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

**I have worked on some projects in the realm of Machine Learning, Reinforcement Learning and Natural Language Processing during my graduate and undergraduate studies, some of which are mentioned below:**

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
