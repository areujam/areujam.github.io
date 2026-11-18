---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
excerpt: "Aruzhan Zhamalbek — machine learning, computational biology, scientific computing, and leadership experience."
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

I am an M.Sc. student in Machine Learning at MBZUAI and a bioengineer by training. I evaluate foundation models for oncology, build reproducible genomics pipelines, and study how scientific ML workloads scale across GPUs.

[Email](mailto:aruzhan.zhamalbek@mbzuai.ac.ae) · [LinkedIn](https://www.linkedin.com/in/aruzhanzhamalbek/) · [GitHub](https://github.com/areujam) · [ORCID](https://orcid.org/0009-0004-1683-6192)

Education
======

**Master of Science in Machine Learning**  
Mohamed bin Zayed University of Artificial Intelligence (MBZUAI) · Abu Dhabi, UAE · Aug 2025 – Present  
* UAE government fully funded scholarship · **GPA: 3.7/4**
* Coursework: Mathematics for AI, Probabilistic & Statistical Inference, Parallel & Distributed ML, Big Data Processing, Deep Learning

**Bachelor of Science in Bioengineering**  
New York University Abu Dhabi · Abu Dhabi, UAE · Sep 2021 – May 2025  
* UAE government fully funded scholarship · **Outstanding Leadership Award (2025)** · **GPA: 3.5/4**
* Coursework: ODEs & PDEs, Numerical Methods, Probability & Statistics, Data Structures & Algorithms

Work Experience
======

**Machine Learning Engineer** · Computational Biology & Cancer Regulatory Genomics (CBCRG)<br>
Masdar City, UAE · Aug 2025 – Present
* Develop reproducible Nextflow pipelines on HPC for TB-scale ENCODE regulatory-genomics data, automating ingestion, QC, metadata harmonization, and experiment–control matching.
* Build data-lineage and validation checks that make runs traceable across datasets, configuration changes, and downstream model inputs.
* Extract high-dimensional signal features and flag data-quality anomalies before model training and downstream analysis.

**Machine Learning R&D Intern (Full-time)** · Nexomic<br>
Dublin, Ireland · Remote · May 2026 – Present
* Evaluate and distill multi-omic foundation models for cancer prognosis, using held-out patients to assess how much prognostic signal a 20-gene model retains.
* Contribute to DeepOmic Bench, which compares up to 56 models per dataset with clinical baselines on frozen splits across 4 tasks, 11 datasets, and 12,627 unique patients.
* Co-author five ESMO AI & Digital Oncology Congress posters and two accepted San Antonio Breast Cancer Symposium posters on model transfer, biomarker prediction, and benchmarking.

**Data Engineering Intern (Part-time)** · GenBio AI<br>
Masdar City, UAE · May 2026 – Aug 2026
* Curated and harmonized biomedical interaction datasets for **Interactome-FM**, standardizing knowledge-graph metadata, edge schemas, file inventories, cloud paths, and data provenance.
* Integrated biological reasoning signals by mapping genes, drugs, pathways, regulatory interactions, protein complexes, and ligand–receptor relationships across heterogeneous sources.
* Built and validated enriched graph artifacts with **132,498 nodes, 32.5M edges, and 56 edge types**; managed GCS uploads, GitLab documentation, and reproducible integration workflows.

**Bioinformatician & Genomics Research Fellow** · Amandine's Lab<br>
Abu Dhabi, UAE · May 2025 – Aug 2025
* Optimized end-to-end pipelines using FastQC, Trimmomatic, BWA, and GATK, improving throughput by **10% across 200+ datasets** and standardizing HPC execution.
* Applied PCA, clustering, and population-diversity metrics to identify latent structure and adaptation signals in genomic cohorts.

**Bioengineering Intern** · NYU Tandon School of Engineering<br>
New York, USA · Jun 2024 – Aug 2024
* Automated QC and analysis for high-throughput sequencing datasets with Python and R; selected as one of the **top seven projects** at the UGSRP Symposium.
* Built statistical signal-to-noise analyses to improve confidence in CRISPR-edit validation under noisy experimental conditions.

**Biomedical Engineering Intern** · National Center of Biotechnology<br>
Astana, Kazakhstan · Jun 2023 – Aug 2023
* Improved operational throughput by **25%** through workflow automation and built exploratory analyses and dashboards for AI-assisted diagnostics initiatives.

Research & Engineering Projects
======

**[Oncology Foundation Model Evaluation](/portfolio/oncology-foundation-model/)** · Nexomic · 2026 – Present
* Report DeepOmic’s 25-shot tumour classification result in ESMO AI poster 9P. The model achieved **0.831 macro-F1 vs. 0.784 for Stackix**, a gain of **4.7 percentage points**.

**[Distributed Vision Transformer Training](/portfolio/distributed-vit-training/)** · PyTorch DDP, SLURM, Pipeline Parallelism, Tiny ImageNet · 2026
* Implemented ViT-Base training across SLURM-managed GPU nodes using pipeline and data parallelism to study throughput, memory pressure, and communication cost.
* Profiled scaling efficiency, gradient-synchronization latency, GPU utilization, and inter-stage bottlenecks across batch sizes and node counts; supervised by Qirong Ho at MBZUAI.

**[Privacy-Preserving Federated Learning for Medical Imaging](/portfolio/federated-learning-medical-imaging/)** · PyTorch, FedAvg, FedProx, NIH ChestX-ray14 · 2026
* Designed a multi-hospital simulation for chest X-ray triage on **NIH ChestX-ray14 (112,120 images)** with non-IID partitioning to model hospital-level distribution shifts.
* Implemented and benchmarked FedAvg, FedProx, and q-FedAvg, evaluating accuracy, worst-site performance, inter-site variance, and robustness under heterogeneous data.

**[Population Genomics Pipeline](/portfolio/population-genomics-pipeline/)** · FastQC, BWA, GATK, HPC · 2025
* Built a scalable workflow for 200+ genomes using PCA, ADMIXTURE, and clustering to study domestication and adaptation signals.

Publications & Selected Research
======

**[Numerical Study of Micropillar Based Glaucoma Drainage Devices](https://doi.org/10.1115/IMECE2025-166623)** · ASME IMECE 2025 · Feb 2026
Published in the ASME IMECE 2025 proceedings. Co-authored with N. Aitmukhanbetov, Y. R. Song, and M. Shah; contributed to computational modeling and data validation. DOI: [10.1115/IMECE2025-166623](https://doi.org/10.1115/IMECE2025-166623).

**CRISPR Gene Editing Data Analysis** · NYU Tandon · 2024
Applied Python and R pipelines to high-throughput sequencing data, validating CRISPR edits in support of cancer-progression research.

{% capture conferences %}{% include cv-conferences.md %}{% endcapture %}
{{ conferences | markdownify }}

Leadership & Service
======

**Undergraduate Residential Life Assistant** · MBZUAI Student Life · May 2026 – Present
* Support a safe, inclusive residential community through programming, peer support, community standards, and on-call responsibilities for the 2026–2027 academic year.

**Engineering Representative** · NYUAD Student Government · Aug 2024 – Aug 2025
* Led seven representatives serving 200+ engineering students and organized a career fair with **1,000+ participants**; received the **Outstanding Leadership Award (2025)**.

**Global Career Peer** · Career Development Center, NYU Abu Dhabi · Jan 2025 – May 2025
* Designed a Notion workspace that increased engagement by **20%**, moderated six employer sessions for 200+ participants, and led bootcamps for 80+ students.

**Head of Social Department** · Nazarbayev University Student Council · Sep 2020 – May 2021
* Led a 10-member department, organized 15–20 events with **5,000+ cumulative engagements**, and mentored 600+ foundation students.

Skills
======

* **Languages:** Python, R, Bash, C++, MATLAB
* **ML & data:** PyTorch, scikit-learn, pandas, NumPy, Hugging Face Transformers, contrastive learning, ablation studies
* **Data engineering:** Knowledge graphs, data curation, metadata harmonization, Parquet, Google Cloud Storage, Kubeflow
* **Distributed systems:** SLURM/HPC, PyTorch DDP, pipeline parallelism, data parallelism, Nextflow
* **MLOps & tools:** Docker, Singularity, Git, GitLab, VS Code, version-controlled reproducible pipelines
* **Research areas:** Foundation models, LLM/NLP data preparation, federated learning, Vision Transformers, medical imaging
