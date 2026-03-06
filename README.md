# Towards Interpretable Formal Software Requirements: Empirical Assessment of Open-Source LLMs for LTL to NL Translation

This repository contains the appendix and codes for the ENASE 2026 paper:

"Towards Interpretable Formal Software Requirements: Empirical Assessment of Open-Source LLMs for LTL to NL Translation".

**Authors:** Vimaleswar A (IISER Bhopal), Dr. Arpit Sharma (IISER Bhopal)

**Summary:**
This work presents the first systematic empirical study of open-source Large Language Models (LLMs) for translating Linear Temporal Logic (LTL) specifications into Natural Language (NL) descriptions. The goal is to improve the interpretability of formal specifications for stakeholders who may not be familiar with formal methods. The study follows a two-phase evaluation framework. In Phase-1, 40 open-source LLMs are screened using a composite score combining translation accuracy, cosine similarity, and benchmark performance. The top-performing 50% of models from each size category are then selected for Phase-2. In Phase-2, the selected 16 models are evaluated across 7 prompting strategies, including zero-shot, few-shot, chain-of-thought, and explanation-augmented CoT. Translation quality is assessed using a weighted multi-metric evaluation framework incorporating lexical, syntactic, and semantic similarity metrics across 4 datasets.

The repository contains the details of the models, prompts, datasets, and evaluation code used in the paper.
