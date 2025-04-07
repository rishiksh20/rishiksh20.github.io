---
title: "GPTQ + LoRA Finetuning from Scratch"
collection: projects
permalink: /projects/8-gptq-lora-from-scratch
excerpt: 'In April 2025, I built a complete GPTQ + LoRA finetuning pipeline from scratch to better understand efficient LLM adaptation.'
---

**Efficient Reasoning LLM** is a minimal, transparent, and fully hand-crafted implementation of quantization-aware LoRA finetuning on top of LLaMA 2–7B using **GPTQ**.

This project was born out of a desire to deeply understand what happens under the hood when you combine low-rank adaptation with post-training quantization. Over a weekend, I built every component of the pipeline by hand in **PyTorch**, without using any external quantization or LoRA libraries.

##### Key Components:
1. **Manual GPTQ Quantization**:
   - Implemented **block-wise GPTQ quantization** from scratch using Hessian approximations and backsolve correction.
   - Supported both **int8** and **int4** precision with optional fused 4-bit packing for memory savings.
   - Saved quantized weights with per-channel `scale` and `zero` points for accurate dequantization.

2. **Custom LoRA Layer Injection**:
   - Developed a custom `LoRALinear` module that can be fused with quantized layers.
   - Injected LoRA adapters into `q_proj`, `k_proj`, `v_proj`, and `o_proj` layers only.
   - Ensured stable forward pass even when base weights are quantized.

3. **Finetuning and Evaluation**:
   - Fine-tuned the model using the **GSM8K** dataset with 3 epochs of supervised training.
   - Achieved a **73.01% exact match accuracy**, competitive with existing methods using 4-bit quantization and LoRA.
   - Built an evaluation script that compares predictions to ground truth, parses answers, and computes final accuracy.

##### Results:
- Demonstrated that **quantization-aware LoRA training** can reach ~73% accuracy on GSM8K even when only a small fraction of the model is trained.
- Validated the effectiveness of training on quantized weights without full finetuning or mixed-precision hacks.
- Memory-efficient: quantized layers were as small as ~16MB (from 80MB+ original), without significant performance loss.

##### Future Directions:
- Implement **self-consistency sampling** to boost accuracy during inference.
- Add **support for int4 fused kernels** and **quantized attention** beyond MLP layers.
- Explore finetuning on larger math reasoning datasets like **MetaMathQA** or **GSM-Hard**.
- Extend this project to support **verifier-based reranking** and **CoT reranking** pipelines.

This project has been a hands-on deep dive into efficient LLM adaptation — no fluff, just real math, code, and learning.

You can explore the full codebase here:  
[**GitHub – Efficient Reasoning LLM**](https://github.com/rishiksh20/efficient-reasoning-llm)