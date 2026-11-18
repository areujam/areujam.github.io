---
title: "Multi-Omic Foundation Models for Oncology"
excerpt: "Evaluating multi-omic oncology foundation models on held-out patients and benchmarking against clinical and model baselines."
collection: portfolio
date: 2026-08-01
---

**Stack:** PyTorch, UCSC Xena, foundation models, ablation studies  
**Context:** Nexomic · 2026 – Present

Evaluating and distilling multi-omic foundation models for cancer prognosis. The work uses held-out-patient protocols to measure model transfer and asks how much of a large model’s prognostic signal can be retained by a compact 20-gene model.

**Key work:**
- Contribute to DeepOmic Bench, comparing up to **56 models per dataset** with clinical baselines on frozen splits across **4 tasks, 11 datasets, and 12,627 unique patients**
- Design leakage-resistant evaluations for zero-shot generalization, survival prediction, biomarker prediction, and compact-model distillation
- Co-author five ESMO AI & Digital Oncology Congress posters and two accepted San Antonio Breast Cancer Symposium posters

The work treats evaluation design as a core modeling problem: meaningful oncology benchmarks need frozen patient splits, strong clinical baselines, and explicit tests of whether learned representations transfer to new tumor contexts.

**Reported result (ESMO AI 2026, poster 9P).** In the 25-shot tumour-type classification setting, DeepOmic achieved **0.831 macro-F1**, compared with **0.784** for Stackix, a gain of **4.7 percentage points**. [See the poster citation](/cv/#conference-posters).
