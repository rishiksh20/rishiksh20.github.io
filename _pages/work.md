---
layout: archive
title: "Work Experience"
permalink: /work/
author_profile: true
---

{% include base_path %}

<ul>
<li>**I am currently building ML and Generative AI systems for HP Inc. at LatentView Analytics, including large-scale case-note classification, LLM-based summarization, and telemetry analytics pipelines to monitor and improve device quality.**</li> 
<li>I also have Volunteering Experience driving Environmental Initiatives with real world Data Analysis.</li>
<li>During my time at University of Michigan, I had 2 stints of being a Research Assistant (NLP, LLM) and Graduate Student Instructor (QMSS 301).</li>
<li>**I have an additional ~ 4 years of professional experience in solving real-world problems using AI/ML and Data Science techniques in Technology, Retail, Telecom, and Healthcare domains.** <br> *I was awarded with SPOT Awards on 3 occasions during my tenure at Mu Sigma as a Data Scientist for exceeding project goals, delivering exceptional results and designing optimal solutions.*</li>
</ul>
<br> **For a detailed description of my professional journey, read below:**

{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}
