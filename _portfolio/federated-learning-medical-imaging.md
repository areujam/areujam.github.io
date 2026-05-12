---
title: "Privacy-Preserving Federated Learning for Medical Imaging"
excerpt: "Multi-hospital FL simulation for chest X-ray triage on NIH ChestX-ray14 with non-IID partitioning and fairness evaluation."
collection: portfolio
---

**Stack:** PyTorch, FedAvg, FedProx, q-FedAvg, NIH ChestX-ray14  
**Status:** In progress (2026 – Present)

Designed a multi-hospital federated learning simulation for chest X-ray triage using the NIH ChestX-ray14 dataset (112,120 images). Non-IID partitioning simulates realistic hospital-level data distribution shifts.

**Key work:**
- Implemented and benchmarked FedAvg, FedProx, and q-FedAvg algorithms
- Evaluated per-hospital accuracy, worst-hospital variance, and inter-hospital fairness gaps — analogous to distributed system fairness metrics
- Designed the data partitioning pipeline to reflect clinical heterogeneity across institutions

**Research connection:** Federated learning for medical imaging directly addresses AI safety concerns around data privacy and equitable model performance across underrepresented institutions.
