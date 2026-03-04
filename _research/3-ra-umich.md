---
title: "Research Assistant at University of Michigan"
collection: research
permalink: /research/3-ra-umich
excerpt: 'Jan 2025 - May 2025 <br> LAUNCH Lab <br> LLM Safety & Evaluation Researcher under Dr. Lu Wang'
---

At the University of Michigan’s LAUNCH Lab, my research focused on evaluating the safety and reliability of agentic large language models, with a particular emphasis on detecting and analyzing deceptive or *scheming* behavior in tool-augmented LLM systems.

To study this problem, I designed and implemented a scalable evaluation framework built on the AutoGen agent framework that simulates realistic software engineering environments. Within these environments, LLM agents interact with multi-step tool chains including Git operations, shell commands, file systems, and external APIs. This setup enables systematic stress-testing of model behavior when given the ability to autonomously plan, execute tools, and modify code.

Using this infrastructure, I generated thousands of evaluation scenarios designed to probe whether models exhibit deceptive strategies when pursuing objectives under constraints or oversight. The framework enables large-scale experimentation to measure how LLM agents behave in complex tool-use settings and helps surface potential safety risks in autonomous AI systems.

This work contributes to ongoing efforts in the AI safety community to better understand emergent strategic behavior in advanced language models and to develop robust evaluation methodologies for agentic AI systems.
