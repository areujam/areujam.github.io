---
title: "Distributed Vision Transformer Training"
excerpt: "Parallelizing ViT-Base training on Tiny ImageNet across HPC SLURM clusters using pipeline and data parallelism."
collection: portfolio
date: 2026-09-01
area: "Distributed ML"
stack: ["PyTorch DDP", "SLURM", "Vision Transformers"]
---

**Stack:** PyTorch DDP, SLURM, Pipeline Parallelism, Tiny ImageNet  
**Status:** Completed (2026) · Supervisor: Qirong Ho, MBZUAI

Implemented ViT-Base training on Tiny ImageNet across SLURM-managed GPU nodes using a combination of pipeline and data parallelism. The project studied how throughput, memory pressure, and communication cost changed across batch sizes and node counts.

**Key work:**
- Profiled gradient-synchronization latency, GPU utilization, and inter-stage bottlenecks
- Measured weak and strong scaling efficiency as node counts and batch sizes changed
- Compared communication cost and memory pressure under different parallelization strategies

This project was supervised by Qirong Ho at MBZUAI as part of advanced work in parallel and distributed machine learning.
