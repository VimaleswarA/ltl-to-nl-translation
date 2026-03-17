# Towards Interpretable Formal Software Requirements: Empirical Assessment of Open-Source LLMs for LTL to NL Translation

This repository contains the appendix and codes for the ENASE 2026 paper: "Towards Interpretable Formal Software Requirements: Empirical Assessment of Open-Source LLMs for LTL to NL Translation".

**Authors:** Vimaleswar A (IISER Bhopal), Dr. Arpit Sharma (IISER Bhopal)

**Abstract:**
Formal software requirements specified in Linear Temporal Logic (LTL) provide unambiguous, mathematically verifiable descriptions of software behavior, essential for model checking and runtime verification. However, LTL’s symbolic syntax is inaccessible to most stakeholders, hindering validation, communication, traceability, counterexample debugging, and trust in safety-critical systems. While large language models (LLMs) excel in requirements engineering (RE) tasks, prior research has focused almost exclusively on translating natural language (NL) to temporal logics. Systematic evaluation of the reverse–LTL to human-readable NL descriptions–remains limited. This paper presents the first systematic empirical study of open-source LLMs
for LTL to NL translation. In Phase-1, 40 diverse models are screened for basic interpretability, selecting 16 for detailed analysis. In Phase-2, these models are evaluated using 7 prompting strategies (including explanation-augmented variants) on 80 LTL specifications from 4 public datasets. Translation quality is assessed via a multi-metric framework measuring lexical overlap, syntactic structure, and semantic alignment with reference descriptions. Our results highlight the importance of multi-metric evaluation and show that several small and
medium sized open-source LLMs can outperform larger models under appropriate prompting, indicating that model scale alone is not sufficient to determine translation quality.

The repository contains the details of the models, prompts, datasets, and evaluation code used in the paper.

---
## 📂 Repository Structure

- In this repository, you'll find:

  - `Appendix.pdf` → Supplementary material containing the list of evaluated open-source LLMs, Phase-1 screening results, all 80 LTL formulas used in Phase-2 from the four datasets, prompting templates (P1-P7), and additional experimental details.
  - `Explanation_Evaluation.ipynb` → Jupyter notebook containing evaluation script for explanation evaluation using BARTScore.
  - `Generated_Explanations.pdf` → Contains the explanations generated using ChatGPT that serve as the reference explanations.
  - `Natural_Language_Evaluation.ipynb` → Jupyter notebook containing evaluation scripts for natural language evaluation.
