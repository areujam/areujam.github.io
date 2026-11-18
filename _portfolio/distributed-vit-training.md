---
title: "Distributed Vision Transformer Training"
excerpt: "Parallelizing ViT-Base training on Tiny ImageNet across HPC SLURM clusters using pipeline and data parallelism."
collection: portfolio
date: 2026-09-01
---

**Stack:** PyTorch DDP, SLURM, Pipeline Parallelism, Tiny ImageNet  
**Status:** In progress (2026 – Present) · Supervisor: Qirong Ho, MBZUAI

Implementing ViT-Base training on Tiny ImageNet across SLURM-managed GPU nodes using a combination of pipeline and data parallelism. The project studies how throughput, memory pressure, and communication cost change across batch sizes and node counts.

**Key work:**
- Profiling gradient-synchronization latency, GPU utilization, and inter-stage bottlenecks
- Measuring weak and strong scaling efficiency as node counts and batch sizes change
- Comparing communication cost and memory pressure under different parallelization strategies

This project is supervised by Qirong Ho at MBZUAI as part of advanced work in parallel and distributed machine learning.
