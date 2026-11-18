---
layout: home
permalink: /
title: "Machine Learning Researcher & Engineer"
excerpt: "Aruzhan Zhamalbek builds distributed machine learning systems and scientific data pipelines for computational biology and medical applications."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="home-hero" aria-labelledby="intro-heading">
  <div class="home-hero__copy">
    <p class="eyebrow"><span class="status-dot" aria-hidden="true"></span> Abu Dhabi · ML systems × computational science</p>
    <h1 id="intro-heading">I build machine learning systems for <span>science at scale.</span></h1>
    <p class="home-hero__lead">I’m Aruzhan Zhamalbek, an M.Sc. student in Machine Learning at MBZUAI and a bioengineer by training. My work connects distributed training, foundation-model data, and reproducible scientific computing.</p>
    <div class="home-actions">
      <a class="portfolio-button portfolio-button--primary" href="/portfolio/">Explore my research <span aria-hidden="true">↗</span></a>
      <a class="portfolio-button" href="mailto:aruzhan.zhamalbek@mbzuai.ac.ae">Start a conversation</a>
    </div>
    <ul class="home-links" aria-label="Professional profiles">
      <li><a href="https://github.com/areujam">GitHub</a></li>
      <li><a href="https://www.linkedin.com/in/aruzhanzhamalbek/">LinkedIn</a></li>
      <li><a href="https://orcid.org/0009-0004-1683-6192">ORCID</a></li>
      <li><a href="/cv/">Full CV</a></li>
    </ul>
  </div>
  <div class="home-hero__portrait">
    <div class="portrait-frame">
      <img src="/images/profile.jpg" alt="Portrait of Aruzhan Zhamalbek" width="720" height="900" fetchpriority="high">
      <div class="portrait-caption">
        <span>Currently</span>
        <strong>M.Sc. Machine Learning</strong>
        <small>MBZUAI · GPA 3.7/4</small>
      </div>
    </div>
  </div>
</section>

<section class="impact-strip" aria-label="Selected impact">
  <div><strong>32.5M</strong><span>knowledge-graph edges</span></div>
  <div><strong>TB-scale</strong><span>genomics pipelines</span></div>
  <div><strong>112K+</strong><span>medical images in FL research</span></div>
  <div><strong>200+</strong><span>genomic datasets processed</span></div>
</section>

<section class="home-section" aria-labelledby="focus-heading">
  <div class="section-heading">
    <p class="eyebrow">What I work on</p>
    <h2 id="focus-heading">From mathematical ideas to reliable systems.</h2>
    <p>I’m most useful where scientific questions meet demanding infrastructure: many GPUs, messy biological data, privacy constraints, or workflows that must be reproducible.</p>
  </div>
  <div class="focus-grid">
    <article class="focus-card focus-card--ink">
      <span class="card-index">01</span>
      <h3>Distributed ML</h3>
      <p>Scaled Vision Transformer training across SLURM-managed GPU nodes using data and pipeline parallelism, with careful profiling of throughput, memory, and communication.</p>
      <div class="tag-row"><span>PyTorch DDP</span><span>SLURM</span><span>HPC</span></div>
    </article>
    <article class="focus-card">
      <span class="card-index">02</span>
      <h3>AI for biology</h3>
      <p>Engineering biomedical knowledge graphs and evaluating oncology foundation models to create stronger, less biased biological representations.</p>
      <div class="tag-row"><span>Foundation models</span><span>Knowledge graphs</span></div>
    </article>
    <article class="focus-card">
      <span class="card-index">03</span>
      <h3>Scientific computing</h3>
      <p>Building traceable pipelines for regulatory and population genomics, and studying PDE-driven systems through numerical methods and simulation.</p>
      <div class="tag-row"><span>Nextflow</span><span>Numerical PDEs</span><span>GATK</span></div>
    </article>
  </div>
</section>

<section class="home-section home-section--tinted" aria-labelledby="work-heading">
  <div class="section-heading section-heading--split">
    <div>
      <p class="eyebrow">Experience</p>
      <h2 id="work-heading">Recent work</h2>
    </div>
    <a class="text-link" href="/experience/">View all experience <span aria-hidden="true">→</span></a>
  </div>
  <div class="current-work">
    <article>
      <div class="work-meta"><span>CBCRG</span><time>2025—Now</time></div>
      <h3>Machine Learning Engineer</h3>
      <p>Engineering reproducible Nextflow pipelines for TB-scale ENCODE data on HPC infrastructure.</p>
    </article>
    <article>
      <div class="work-meta"><span>Nexomic</span><time>2026—Now</time></div>
      <h3>Machine Learning R&D Intern</h3>
      <p>Evaluate and distill oncology foundation models and contribute to DeepOmic Bench, which spans 12,627 unique patients.</p>
    </article>
    <article>
      <div class="work-meta"><span>GenBio AI</span><time>May—Aug 2026</time></div>
      <h3>Data Engineering Intern</h3>
      <p>Built Interactome-FM training graphs with 132,498 nodes, 32.5M edges, and 56 biological relationship types.</p>
    </article>
  </div>
</section>

<section class="home-section" aria-labelledby="projects-heading">
  <div class="section-heading section-heading--split">
    <div>
      <p class="eyebrow">Selected research</p>
      <h2 id="projects-heading">Systems with a scientific purpose.</h2>
    </div>
    <a class="text-link" href="/portfolio/">All projects <span aria-hidden="true">→</span></a>
  </div>
  <div class="project-showcase">
    <a class="project-feature" href="/portfolio/distributed-vit-training/">
      <span class="project-kicker">Distributed systems · 2026</span>
      <h3>Scaling Vision Transformer training across GPU nodes</h3>
      <p>Combining pipeline and data parallelism to understand how synchronization, utilization, and inter-stage bottlenecks shape performance.</p>
      <span class="project-arrow" aria-hidden="true">↗</span>
    </a>
    <a class="project-feature" href="/portfolio/federated-learning-medical-imaging/">
      <span class="project-kicker">Medical AI · 2026</span>
      <h3>Privacy-preserving learning across simulated hospitals</h3>
      <p>Benchmarking federated algorithms under realistic non-IID chest X-ray distributions and measuring worst-site performance.</p>
      <span class="project-arrow" aria-hidden="true">↗</span>
    </a>
    <a class="project-feature project-feature--wide" href="/publication/2026-02-01-micropillar-glaucoma-drainage">
      <span class="project-kicker">Published research · ASME IMECE 2025</span>
      <h3>Numerical Study of Micropillar Based Glaucoma Drainage Devices</h3>
      <p>Computational modeling and data validation for microfluidic glaucoma drainage design. DOI: 10.1115/IMECE2025-166623.</p>
      <span class="project-arrow" aria-hidden="true">↗</span>
    </a>
  </div>
</section>

<section class="home-section education-band" aria-labelledby="education-heading">
  <div class="section-heading">
    <p class="eyebrow">Education</p>
    <h2 id="education-heading">Bioengineering foundations. Machine learning depth.</h2>
  </div>
  <div class="education-grid">
    <article>
      <span class="education-year">2025—Present</span>
      <h3>Mohamed bin Zayed University of AI</h3>
      <p>M.Sc. in Machine Learning · GPA 3.7/4<br>UAE government fully funded scholarship</p>
    </article>
    <article>
      <span class="education-year">2021—2025</span>
      <h3>New York University Abu Dhabi</h3>
      <p>B.Sc. in Bioengineering · GPA 3.5/4<br>Outstanding Leadership Award, 2025</p>
    </article>
  </div>
</section>

<section class="home-cta" aria-labelledby="contact-heading">
  <p class="eyebrow">Let’s connect</p>
  <h2 id="contact-heading">Interested in ML systems, computational biology, or ambitious scientific infrastructure?</h2>
  <a href="mailto:aruzhan.zhamalbek@mbzuai.ac.ae">aruzhan.zhamalbek@mbzuai.ac.ae <span aria-hidden="true">↗</span></a>
</section>
