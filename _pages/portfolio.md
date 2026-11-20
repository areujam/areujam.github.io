---
layout: wide
title: "Research & Engineering"
permalink: /portfolio/
excerpt: "Selected work in distributed machine learning, computational biology, medical AI, and scientific computing."
author_profile: false
---

<section class="wide-hero wide-hero--research">
  <div>
    <p class="eyebrow">Selected research & engineering</p>
    <h1>Systems that make scientific questions <span>computable.</span></h1>
    <p class="wide-hero__lead">My work moves between models and infrastructure: distributed training, multi-omic foundation models, privacy-preserving medical AI, and reproducible genomics pipelines.</p>
  </div>
  <div class="research-compass" aria-label="Research themes">
    <span>Distributed ML</span>
    <span>AI for biology</span>
    <span>Scientific computing</span>
    <strong>ML × SCIENCE</strong>
  </div>
</section>

<section class="research-principles" aria-label="How I work">
  <div><span>01</span><strong>Scale deliberately</strong><p>Measure the bottleneck before adding complexity.</p></div>
  <div><span>02</span><strong>Keep lineage visible</strong><p>Make data and experiments traceable end to end.</p></div>
  <div><span>03</span><strong>Evaluate honestly</strong><p>Use held-out patients, strong baselines, and clear limitations.</p></div>
</section>

<section class="research-index" aria-labelledby="research-index-heading">
  <div class="section-heading section-heading--split">
    <div>
      <p class="eyebrow">Project index</p>
      <h2 id="research-index-heading">Explore the work</h2>
    </div>
    <a class="text-link" href="/posters/">See conference outputs <span aria-hidden="true">→</span></a>
  </div>

  <div class="research-grid">
    {% assign sorted_projects = site.portfolio | sort: 'date' | reverse %}
    {% for post in sorted_projects %}
      <a class="research-card" href="{{ post.url }}">
        <div class="research-card__topline">
          <span>{{ post.area | default: "Research project" }}</span>
          <time>{{ post.date | date: "%Y" }}</time>
        </div>
        <h2>{{ post.title }}</h2>
        <p>{{ post.excerpt }}</p>
        {% if post.stack %}<div class="tag-row">{% for item in post.stack %}<span>{{ item }}</span>{% endfor %}</div>{% endif %}
        <span class="research-card__arrow" aria-hidden="true">↗</span>
      </a>
    {% endfor %}
  </div>
</section>

<section class="research-publication">
  <div>
    <p class="eyebrow">Peer-reviewed publication</p>
    <h2>Numerical Study of Micropillar Based Glaucoma Drainage Devices</h2>
    <p>Computational modeling and data validation for microfluidic glaucoma drainage design, published in the ASME IMECE 2025 proceedings.</p>
  </div>
  <div>
    <span>DOI</span>
    <a href="https://doi.org/10.1115/IMECE2025-166623">10.1115/IMECE2025-166623 ↗</a>
  </div>
</section>
