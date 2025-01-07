---
title: "PapeRet: Research Paper Retrieval System"
collection: projects
permalink: /projects/6-PapeRet
excerpt: 'From September to December 2024, I worked on a course project for SI 650 Information Retrieval course at University of Michigan.'
paperurl: 'http://rishiksh20.github.io/files/paperet-report.pdf'
---


**PapeRet** is a specialized Information Retrieval (IR) system designed to address the challenges of efficiently retrieving academic research papers in machine learning, AI, and NLP. The system combines traditional IR techniques with advanced NLP methods to enhance search precision and deliver meaningful results.

##### Key Features:
1. **Recursive Metadata Collection**:
   - Utilized the **OpenAlex API** and **ArXiv API** to gather metadata for ~98,000 papers, starting from 30 influential seed papers and recursively expanding the dataset.
   - Implemented web scraping and PDF parsing to extract full-text content, overcoming challenges like rate limits, CAPTCHA protections, and diverse website structures.

2. **Advanced Query Processing**:
   - Integrated **TF-IDF** and **BM25 rankers** with enhanced query augmentation techniques.
   - Leveraged **zero-shot inference using LLaMA** for query tokenization, enabling structured extraction of keywords, authors, and temporal constraints.
   - Introduced weighted scoring, author/year boosting, and re-ranking strategies for improved retrieval.

3. **Summarization and UI**:
   - Developed concise, retrieval-augmented summaries using **LLaMA’s Retrieval-Augmented Generation (RAG)**.
   - Built a **Streamlit-based UI** for intuitive interaction, enabling users to perform parameterized searches and view AI-generated summaries.

##### Results:
- Processed ~98,000 research papers with a final curated dataset.
- Achieved a **MAP@10 of 0.539** and **NDCG@10 of 0.81**, significantly outperforming baseline approaches.
- Enabled precise searches for complex queries, such as author-specific works or multi-modal topics.

##### Future Directions:
- Explore **supervised fine-tuning** of LLaMA for improved query understanding.
- Refine PDF parsing methods for higher accuracy in full-text extraction.
- Extend the system to visualize citation networks and identify research gaps.

**PapeRet** provides a robust framework for navigating the growing corpus of academic literature, offering researchers a powerful tool to streamline their workflows and focus on innovation.


You can find the codebase on [GitHub](https://github.com/nilaygautam2007/PapeRet/tree/main).