---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
**Master of Science in Machine Learning**  
Mohamed bin Zayed University of Artificial Intelligence (MBZUAI) · Abu Dhabi, UAE · Aug 2025 – Present  
* UAE government fully funded scholarship · GPA: 3.7/4  
* Coursework: Parallel & Distributed ML, Big Data Processing, Deep Learning, Medical Imaging, Probabilistic & Statistical Inference, Mathematics for AI

**Bachelor of Science in Bioengineering**  
New York University Abu Dhabi · Abu Dhabi, UAE · Sep 2021 – May 2025  
* UAE government fully funded scholarship · Outstanding Leadership Award (2025) · GPA: 3.5/4  
* Coursework: Data Structures & Algorithms, Cyberwarfare, Numerical Methods, Probability & Statistics, ODEs & PDEs

Work Experience
======
**Machine Learning Engineer** · Computational Biology & Cancer Regulatory Genomics (CBCRG)  
Masdar City, UAE · Aug 2025 – Present  
* Engineered reproducible ML data pipelines on HPC infrastructure using Nextflow, processing TB-scale heterogeneous ENCODE datasets with automated quality validation and metadata reconciliation.
* Built experiment–control pair matching system enabling data lineage, traceability, and reproducibility.
* Performed high-dimensional signal extraction and anomaly detection on noisy large-scale datasets.

**Bioinformatician and Genomics Research Fellow** · Amandine's Lab  
Abu Dhabi, UAE · May 2025 – Aug 2025  
* Optimized end-to-end data processing pipelines (FastQC, Trimmomatic, BWA, GATK), increasing throughput by 10% across 200+ datasets; containerized all workflows for HPC reproducibility.
* Applied unsupervised learning (PCA, clustering, diversity metrics) to uncover latent structure in large datasets.

**Bioengineering Intern** · NYU Tandon School of Engineering  
New York, USA · Jun 2024 – Aug 2024  
* Analyzed high-volume sequencing datasets using Python and R pipelines, automating QC checks; delivered findings as one of the top 7 selected projects at the UGSRP Symposium.
* Developed statistical signal-to-noise models to improve confidence in automated validation under noisy data conditions.

**Biomedical Engineering Intern** · National Center of Biotechnology  
Astana, Kazakhstan · Jun 2023 – Aug 2023  
* Improved operational throughput by 25% through process automation; conducted exploratory data analysis and dashboarding for AI-driven diagnostic initiatives.

Research & Engineering Projects
======
**Distributed Vision Transformer Training** · PyTorch DDP, SLURM, Pipeline Parallelism, Tiny ImageNet · 2026 – Present  
* Parallelizing ViT-Base training on Tiny ImageNet across HPC SLURM cluster using pipeline parallelism and data parallelism, targeting distributed inference and throughput optimization at scale.
* Benchmarking communication overhead, gradient synchronization latency, and scaling efficiency across multiple GPU nodes (supervisor-approved, Qirong Ho, MBZUAI).

**Privacy-Preserving Federated Learning for Medical Imaging** · PyTorch, FedAvg, FedProx, NIH ChestX-ray14 · 2026 – Present  
* Designed multi-hospital FL simulation for chest X-ray triage on NIH ChestX-ray14 (112,120 images) with non-IID partitioning to simulate realistic hospital-level distribution shifts.
* Implemented and benchmarked FedAvg, FedProx, and q-FedAvg; evaluating per-hospital accuracy, worst-hospital variance, and inter-hospital fairness gaps.

**Population Genomics Pipeline** · FastQC, BWA, GATK, HPC · 2025  
* Built scalable HPC workflow for 200+ genomes incorporating PCA, ADMIXTURE, and clustering to study domestication and adaptation signals at scale.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Languages:** Python, R, Bash, C++, MATLAB
* **ML / Frameworks:** PyTorch, scikit-learn, pandas, NumPy, Hugging Face Transformers
* **Distributed Systems:** SLURM/HPC, PyTorch DDP, Pipeline Parallelism, Data Parallelism, Nextflow
* **MLOps & Tools:** Docker/Singularity, Git, version-controlled reproducible pipelines
* **Research Areas:** Federated Learning, Vision Transformers, Distributed Training, Large-scale Data Pipelines

Leadership & Service
======
**Engineering Representative** · NYUAD Student Government · Aug 2024 – Aug 2025  
* Led 7 representatives serving 200+ engineering students; organized career fair with 1,000+ participants. Awarded Outstanding Leadership Award (2025).

**Global Career Peer** · Career Development Center, NYU Abu Dhabi · Jan 2025 – May 2025  
* Designed Notion workspace boosting student engagement by 20%; moderated 6 employer sessions with 200+ participants; led bootcamps for 80+ students.

**Head of Social Department** · Nazarbayev University Student Council · Sep 2020 – May 2021  
* Led 10-member department; organized 15–20 events with 5,000+ cumulative engagements; mentored 600+ foundation students, increasing engagement by 10%.
