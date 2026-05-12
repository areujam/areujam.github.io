---
title: "Distributed Vision Transformer Training"
excerpt: "Parallelizing ViT-Base training on Tiny ImageNet across HPC SLURM clusters using pipeline and data parallelism."
collection: portfolio
---

**Stack:** PyTorch DDP, SLURM, Pipeline Parallelism, Tiny ImageNet  
**Status:** In progress (2026 – Present) · Supervisor: Qirong Ho, MBZUAI

Parallelizing ViT-Base training on Tiny ImageNet across an HPC SLURM cluster using a combination of pipeline parallelism and data parallelism, targeting distributed inference and throughput optimization at scale.

**Key work:**
- Benchmarking communication overhead and gradient synchronization latency across multiple GPU nodes
- Measuring scaling efficiency (weak and strong scaling) as node count increases
- Targeting production-level distributed inference patterns

This project is part of the Parallel & Distributed ML coursework at MBZUAI, with supervisor approval from Prof. Qirong Ho.
