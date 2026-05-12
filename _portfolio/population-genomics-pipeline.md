---
title: "Population Genomics Pipeline"
excerpt: "Scalable HPC workflow for 200+ genomes incorporating PCA, ADMIXTURE, and clustering to study domestication and adaptation signals."
collection: portfolio
---

**Stack:** FastQC, Trimmomatic, BWA, GATK, HPC (SLURM), R  
**Status:** Completed (2025) · Amandine's Lab, NYUAD

Built a scalable, reproducible HPC workflow for processing and analyzing 200+ genomes. The pipeline covers the full genomics stack from raw read QC to population structure inference.

**Key work:**
- End-to-end pipeline: FastQC → Trimmomatic → BWA alignment → GATK variant calling
- Downstream population analysis: PCA, ADMIXTURE, clustering to study domestication signals and local adaptation
- Containerized all workflow steps with Singularity for HPC reproducibility
- Increased throughput by 10% through pipeline optimization

The project demonstrates the same engineering principles as large-scale ML data pipelines: reproducibility, containerization, parallel execution, and automated quality validation.
