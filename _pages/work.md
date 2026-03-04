---
layout: archive
title: "Work Experience"
permalink: /work/
author_profile: true
---

{% include base_path %}

<ul>
<li>I am currently building machine learning and Generative AI systems for HP Inc. at LatentView Analytics, including large-scale case-note classification, LLM-based summarization, and telemetry analytics pipelines to monitor and improve device reliability.</li>

<li>I have also contributed to environmental and nonprofit initiatives through data analysis and digital analytics work supporting conservation and outreach efforts.</li>

<li>During my time at the University of Michigan, I worked as both a Research Assistant (NLP and LLM safety research) and a Graduate Student Instructor for QMSS 301: Quantitative Social Science Analysis and Big Data.</li>

<li>I bring ~4 years of additional industry experience applying AI/ML and data science to real-world problems across technology, telecom, retail, and healthcare domains. <i>I received three SPOT Awards at Mu Sigma for delivering high-impact analytical solutions.</i></li>
</ul>

**For a detailed description of my professional journey, see the roles below.**


{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}
