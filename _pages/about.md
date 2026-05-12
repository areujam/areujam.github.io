---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Machine Learning Master's student at MBZUAI with a background in Bioengineering (NYUAD). My work sits at the intersection of **ML systems engineering** and **computational biology** — I build scalable distributed training pipelines, HPC infrastructure, and reproducible ML workflows.

Currently I am implementing Vision Transformer parallelization (pipeline + data parallelism) on SLURM/HPC clusters and federated learning systems for privacy-preserving medical imaging. I am also a Machine Learning Engineer at the [Computational Biology & Cancer Regulatory Genomics Lab (CBCRG)](https://khanlab.bio/), where I engineer TB-scale ML data pipelines on HPC infrastructure using Nextflow.

I am actively seeking roles in **ML systems engineering**, **AI infrastructure**, and **safety-relevant distributed ML research**.

---

## Education

**Master of Science in Machine Learning**  
*Mohamed bin Zayed University of Artificial Intelligence (MBZUAI)* · Abu Dhabi, UAE · Aug 2025 – Present  
- UAE government fully funded scholarship · GPA: 3.7/4  
- Coursework: Parallel & Distributed ML, Big Data Processing, Deep Learning, Medical Imaging, Probabilistic & Statistical Inference, Mathematics for AI

**Bachelor of Science in Bioengineering**  
*New York University Abu Dhabi (NYUAD)* · Abu Dhabi, UAE · Sep 2021 – May 2025  
- UAE government fully funded scholarship · Outstanding Leadership Award (2025) · GPA: 3.5/4  
- Capstone: "Numerical Study of Micropillar-Based Glaucoma Drainage Devices" — presented at ASME IMECE 2025

---

## Research & Engineering Projects

**Distributed Vision Transformer Training** · PyTorch DDP, SLURM, Pipeline Parallelism · 2026 – Present  
Parallelizing ViT-Base training on Tiny ImageNet across HPC SLURM clusters using pipeline and data parallelism. Benchmarking communication overhead, gradient synchronization latency, and scaling efficiency across multiple GPU nodes.

**Privacy-Preserving Federated Learning for Medical Imaging** · PyTorch, FedAvg, FedProx · 2026 – Present  
Multi-hospital FL simulation for chest X-ray triage on NIH ChestX-ray14 (112,120 images) with non-IID partitioning. Benchmarking FedAvg, FedProx, and q-FedAvg; evaluating per-hospital accuracy and inter-hospital fairness gaps.

**Population Genomics Pipeline** · FastQC, BWA, GATK, HPC · 2025  
Scalable HPC workflow for 200+ genomes incorporating PCA, ADMIXTURE, and clustering to study domestication and adaptation signals at scale.

---

## Skills

**Languages:** Python, R, Bash, C++, MATLAB  
**ML / Frameworks:** PyTorch, scikit-learn, pandas, NumPy, Hugging Face Transformers  
**Distributed Systems:** SLURM/HPC, PyTorch DDP, Pipeline Parallelism, Data Parallelism, Nextflow  
**MLOps & Tools:** Docker/Singularity, Git, version-controlled reproducible pipelines  
**Research Areas:** Federated Learning, Vision Transformers, Distributed Training, Large-scale Data Pipelines
