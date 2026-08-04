---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

📄 **[Download a PDF version of my resume.](https://rishiksh20.github.io/files/Resume%20-%20Rishikesh%20Ajay%20Ksheersagar%20-%20Aug26.pdf)**


# Rishikesh Ajay Ksheersagar

Houston, TX | [rishikesh.ksheersagar@gmail.com](mailto:rishikesh.ksheersagar@gmail.com) | [https://www.linkedin.com/in/rishikeshksheersagar/](https://www.linkedin.com/in/rishikeshksheersagar/) | [https://rishiksh20.github.io/](https://rishiksh20.github.io/)

## PROFILE

- *Skills:* Machine Learning (ML), Large Language Models (LLMs), Agentic AI, LangGraph, LangChain, AutoGen, Retrieval Augmented Generation (RAG), Computer Vision (CV), Deep Learning, Natural Language Processing (NLP), Anomaly Detection, Regression Analysis, Statistical Inference, Reinforcement Learning (RL), Information Retrieval, CI/CD
- *Languages:* Python (Pandas, NumPy, ScikitLearn, Tensorflow, PyTorch, OpenCV, NLTK, Spacy), SQL, PySpark, R, C++
- *Tools / Platforms:* Azure, Snowflake, Hadoop, GCP, AWS, Jenkins, Tableau, PowerBI

## EDUCATION

### University of Michigan - Ann Arbor | August 2023 - May 2025

*Masters in Data Science*, GPA 4.0/4.0 | Ann Arbor, MI, USA

Subjects: CSE 595 (NLP), ECE 598 (LLMs), CSE 545 (ML), SI 650 (Information Retrieval), STATS 510 (Probability Distributions)

### Savitribai Phule Pune University | June 2015 - June 2019

*Bachelor of Engineering in Computer Engineering*, GPA 3.7/4.0 | Pune, India

## PROFESSIONAL EXPERIENCE

### LATENTVIEW ANALYTICS | November 2025 - Present

***Data Scientist*** | Houston, TX, USA

- Productionized a multi-turn, multimodal agentic RAG system using LangGraph and Azure AI Search, delivering grounded Q&A across 2,500+ equipment manuals (300+ pages each) for 100+ concurrent users with p95 TTFT of 8s and p95 completion latency of 25s.
- Architected hierarchical summary-to-chunk hybrid retrieval with SLM-based routing and reranking; built an async FastAPI serving layer with per-thread Redis locks, custom SQL-backed LangGraph checkpointing, 4-hour retrieval caching, and Phoenix tracing and metrics.
- Delivered an end-to-end CV-LLM proof of concept that detects regulatory labels and certification marks in product artwork PDFs, validates them against approval-specific requirements, and flags compliance gaps, demonstrating a ~60% reduction in manual review time.
- Spearheaded a hybrid detection pipeline combining raster contour analysis, PDF vector-path extraction, multimodal classification, bounding-box refinement, Object Detection (YOLO) and multi-scale template matching with LLM fallback to support diverse artwork formats without labeled training data.
- Developed Generative AI - powered summarization and BERT-based case-note classification pipelines to transform large-scale telemetry device-health and reliability data into structured, and actionable reports for engineering and leadership.

### UNIVERSITY OF MICHIGAN | May 2024 - May 2025

***Research Assistant*** | Ann Arbor, MI, USA

- Engineered a scalable AutoGen evaluation framework that stress-tests LLMs for deceptive (scheming) behavior across thousands of realistic SWE scenarios, dynamically exercising multi-tool chains (Git, shell, file, and 2k+ live APIs) to measure safe tool use at scale.
- Completed NLP research on "Climate Change, Demographic Shifts, and Socio-Political Stability in Sub-Saharan Africa" under the Minerva Initiative. Automated metadata retrieval, PDF scraping, and text extraction for 50k+ research papers. Analyzed 20k+ causal sentences linking climate change and social unrest using POS tagging and LLMs.

***Graduate Student Instructor***

- Conducted weekly lab sessions for 60+ students in the QMSS 301 course during Fall 2024 and Winter 2025 semester, topics include - Geospatial Analysis in R, Predictive Modeling and Sentiment Analysis in Python, Web Scraping, and Research Methodologies.

### MU SIGMA INC. | July 2019 - June 2023

***Apprentice Leader*** | Bangalore, India

- Managed 2 teams consisting of 8 data scientists working with Fortune-100 clients in Telecom and Healthcare domains, spearheaded the growth and management of engagements generating $1M annually.
- Achieved a 30% decrease in probable outages by designing an unbalanced multi-class classifier model using RxMER data, stacking XGBoost and sequential Neural Network models to precisely identify causation of Modem Network Impairment Anomalies in near real-time.
- Developed a capability-building PoC tool to simulate Patient Journeys in Clinical Trials by integrating Therapeutic Area, Site, PI, Patient, and Trial attributes, utilizing Bayesian Networks and Agent-Based Models enabling proactive planning and mid-trial adjustments for Phase 3 Clinical Trials
- Drove RFP connects with CXOs of 2 Fortune-100 Telecom clients showcasing deep domain expertise and strategic solution alignment.

***Decision Scientist***

- Led a team of 7 data scientists in identifying key features for degraded network service for the Data Science and Data Engineering team of a Fortune-100 Telecom clientele.
- Delivered 98.7% accuracy in detecting degraded network service events by conducting Statistical Analyses and Hypotheses Testing on 7 datasets including Cable Modem Registration, Speed Tests, Modem Utilization, and designing an Anomaly Detection framework.
- Reduced execution time by 60% by enabling Digital Transformation for a legacy Store Planning tool for the FP&A team of the world's largest Home Improvement Retailer by migrating from a SAS - FileZilla system to a Machine Learning backed Python - GCP based solution.
- Enabled the clients generate historically aligned financial plans for 8 Retail Metrics via constrained optimization and time series models.
- Designed a Failure Tracking system which reduced the Tool Failures by 50% and decreased the debugging time by 75% by automating the failure root cause analyses process and dynamically rectifying the failures thus reducing manual interventions.
- Created 7 Tableau Dashboards to provide detailed insights and flag anomalies in Financial Plans for key retail metrics.

### BMC SOFTWARE | August 2018 - April 2019

***Project Intern*** | Pune, India

- Worked on a PoC which involved implementation of private Blockchain with voting-based consensus mechanism by leveraging Hyperledger Composer, in addition to a traditional Structured Database, in the backend of a globally used legacy ITSM Software.

## ACADEMIC PROJECTS

- **Efficient Reasoning LLM (Apr 2025)** - Implemented 4-bit GPTQ quantization and LoRA fine-tuning from scratch in PyTorch for LLaMA 2 7B on GSM8K, including Hessian-aware block wise quantization, INT4 packing, quantized matrix multiplication, and custom attention adapters. Fine-tuned the model on a single A100 in ~45 minutes and achieved ~73% accuracy. [GitHub](https://github.com/rishiksh20/efficient-reasoning-llm)
- **PapeRet (Sept - Dec 2024)** - Designed a research paper retrieval system, processing 98,000+ academic papers using recursive metadata extraction, web scraping, PDF download and text extraction. Leveraged LLaMA for Retrieval-Augmented Generation (RAG) to create summaries. Achieved significant performance improvements, with MAP@10 of 0.539 and NDCG@10 of 0.81. [GitHub](https://github.com/nilaygautam2007/PapeRet)[Report](https://github.com/nilaygautam2007/PapeRet/blob/main/PapeRet.pdf)
- **Register Augmented LLM Fine-Tuning (Oct - Dec 2024)** - Developed a register-augmented fine-tuning approach for LLMs, enhancing global context management and interpretability. Implemented RegBERT for QA tasks, improving F1 and Exact Match scores on the TyDiQA GoldP dataset, with attention analysis using Layer-wise Relevance Propagation (LRP) and Integrated Gradients. [GitHub](https://github.com/5hloke/Register_augmented_fine_tuning/tree/qa-relprop)[Report](https://github.com/5hloke/Register_augmented_fine_tuning/blob/qa-relprop/EECS_598_LLMs.pdf)
- **Few-Shot Preference-Based RLHF (Jan - May 2024)** - Implemented and refined few-shot preference-based reinforcement learning algorithms, including MAML, iterated MAML, and REPTILE, to optimize human feedback efficiency on Metaworld datasets. Developed a generalized reward function adaptable to new tasks with minimal human queries and ~90% reduction in training time. [GitHub](https://github.com/5hloke/Few-Shot-Learning-RL-prior-policy)[Report](http://rishiksh20.github.io/files/ml-report.pdf)
- **Is it easy to be Multilingual (Nov - Dec 2023)** - Explored mBERT's transfer mechanics, emphasizing syntactic, morphological, and phonological similarities as key predictors. Displayed language model performance's critical role in cross-lingual transfer. Proposed a framework achieving 62.5% accuracy in selecting optimal source language for multilingual cross-transfer. [GitHub](https://github.com/EECS595-Multilingual/Is-it-easy-to-be-multilingual)[Report](https://github.com/EECS595-Multilingual/Is-it-easy-to-be-multilingual/blob/main/Documents/Report%20-%20Is%20it%20easy%20to%20be%20Multilingual.pdf)

## HONORS AND AWARDS

- **Mu Sigma Inc.:** Received SPOT Awards in 3 consecutive years (Aug 2022, Aug 2021, Oct 2020) for exceeding project goals, delivering exceptional results and designing optimal solutions.