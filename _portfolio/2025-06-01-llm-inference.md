---
title: "Large Language Model Inference System"
excerpt: "Multi-model ensemble, LoRA, cached kv, RAG, FAISS · +10% accuracy, +60% inference speed"
collection: portfolio
date: 2025-06-01
tags: [LLM, RAG, Inference, FAISS, LangChain, LoRA]
---

- 多模型集成（Mistral-7B, Yi-34B, LLaMA2），Zero-shot/Few-shot/SFT（配合 H2O LLM Studio）。  
- LoRA + `past_key_values` 缓存，加速 **~60%**。  
- 构建 **6000 万段**维基语料，FAISS 向量检索 + Prompt 设计做 RAG。  
- 置信度融合 + TF-IDF rerank + embedding 相似度，Top-3 命中率 **93%**，整体准确率较单模 **+15%**。
