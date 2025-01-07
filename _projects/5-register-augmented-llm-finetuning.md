---
title: "Register Augmented LLM Fine-tuning"
collection: projects
permalink: /projects/5-register-augmented-llm-finetuning
excerpt: 'From October to December 2024, I worked on a course project for ECE 598 Special Topics - Large Language Models course at University of Michigan.'
paperurl: 'http://rishiksh20.github.io/files/reg-aug-ft-report.pdf'
slidesurl: 'http://rishiksh20.github.io/files/reg-aug-ft-poster.pdf'
---

This project introduced a novel fine-tuning approach for Large Language Models (LLMs) by integrating **register tokens** into transformer architectures. Inspired by Vision Transformers, the approach uses empty register tokens to better manage global context and reduce artifacts in attention mechanisms, such as high-norm tokens. These tokens offload less critical computations, allowing the model to focus on task-relevant details.

##### Key Contributions:
1. **Development of RegBERT**: 
   - Extended BERT by appending register tokens and modifying embeddings and attention mechanisms.
   - Designed RegBERTForQA for Question-Answering tasks, optimizing predictions and excluding registers during inference.

2. **Improved Performance**:
   - Conducted ablation studies to identify optimal register configurations, achieving significant F1 and Exact Match improvements on the **TyDi QA GoldP dataset**.

3. **Attention Analysis**:
   - Used **Layer-wise Relevance Propagation (LRP)** to visualize improved focus and interpretability in attention mechanisms.
   - Applied **Integrated Gradients** to quantify token contributions, highlighting the systematic processing enabled by register tokens.

##### Results:
- Register tokens consistently enhanced performance, with optimal results using 5-10 tokens.
- Attention maps showed reduced noise and better focus on relevant information.

##### Future Directions:
The study opens possibilities for applying register augmentation to other NLP tasks, testing its robustness across architectures and languages, and further analyzing individual token roles. 

This work demonstrates the potential of register-augmented fine-tuning to improve LLM performance, interpretability, and efficiency in complex NLP tasks.

You can find the codebase on [GitHub](https://github.com/5hloke/Register_augmented_fine_tuning/tree/qa-relprop).