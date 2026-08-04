---
title: "Data Scientist"
collection: work
permalink: /work/6-data-scientist-lv
excerpt: "LatentView Analytics (CW at HP Inc.), Houston, TX, USA <br> November 2025 - Present"
---


## Data Scientist — HP Personal Systems Quality AI & Analytics

At LatentView Analytics, I work as a Data Scientist supporting HP’s Personal Systems Quality team, where I engineer scalable machine learning and Generative AI systems across agentic RAG, multimodal document intelligence, support analytics, and device telemetry. My work spans the complete AI engineering lifecycle—from system and retrieval architecture to deployment, observability, performance optimization, and business integration.

### Key Contributions

* **Productionized a multi-turn, multimodal agentic RAG system** using LangGraph and Azure AI Search, delivering grounded Q&A across 2,500+ equipment manuals containing 300+ pages each. The system supports 100+ concurrent users with a p95 time to first token of 8 seconds and p95 completion latency of 25 seconds.

* **Architected the retrieval and serving infrastructure** using hierarchical summary-to-chunk hybrid retrieval, small-language-model routing and reranking, asynchronous FastAPI endpoints, per-thread Redis locks, custom SQL-backed LangGraph checkpointing, four-hour retrieval caching, and Phoenix-based tracing and performance monitoring.

* **Delivered an end-to-end CV-LLM compliance automation proof of concept** that detects regulatory label regions and certification marks in product artwork PDFs, validates them against approval-specific requirements, and flags missing or extraneous marks—demonstrating a potential ~60% reduction in manual review time.

* **Developed Generative AI support-analytics pipelines** for large-scale case-note summarization and BERT-based multi-level issue classification, transforming hundreds of thousands of unstructured support records into structured, actionable reliability insights.

* **Built semantic embedding and clustering pipelines** using Sentence Transformers and Azure Databricks to support similarity search, taxonomy development, representative sampling, and emerging-issue discovery across large support datasets.

* **Engineered PySpark telemetry analytics pipelines** to monitor boot performance, battery health, thermal behavior, BIOS compliance, and system events across millions of devices, enabling proactive reliability monitoring and engineering dashboards.

### Technologies

Python • LangGraph • Azure OpenAI • Azure AI Search • FastAPI • Redis • Arize Phoenix • SQL • PySpark • Azure Databricks • Sentence Transformers • BERT • OpenCV • PyMuPDF • RAG • NLP • Multimodal AI • Vector Search • Power BI
