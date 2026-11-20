---
layout: wide
title: "Posters & Abstracts"
permalink: /posters/
excerpt: "Conference posters, accepted work, and research currently under review."
author_profile: false
---

<section class="wide-hero wide-hero--outputs">
  <div>
    <p class="eyebrow">Research communication</p>
    <h1>Ideas in motion—<span>from poster hall to peer review.</span></h1>
    <p class="wide-hero__lead">A living record of my conference work in multi-omic foundation models, oncology, and computational biology. The five ESMO AI posters are now available to preview and open in full resolution.</p>
  </div>
  <div class="output-tally" aria-label="Research output summary">
    <div><strong>5</strong><span>ESMO AI posters</span></div>
    <div><strong>2</strong><span>SABCS accepted</span></div>
    <div><strong>8</strong><span>ASCO GI in review</span></div>
    <div><strong>1</strong><span>AACR in review</span></div>
  </div>
</section>

<section class="output-explainer" aria-label="Status guide">
  <p><strong>Presented</strong> work includes the full poster PDF.</p>
  <p><strong>Accepted</strong> work has a confirmed conference decision.</p>
  <p><strong>Under review</strong> is listed without implying acceptance.</p>
</section>

<section class="outputs-section" aria-labelledby="outputs-heading">
  <div class="section-heading section-heading--split">
    <div>
      <p class="eyebrow">Conference pipeline</p>
      <h2 id="outputs-heading">Browse the work</h2>
    </div>
    <div class="output-filters" role="group" aria-label="Filter research outputs">
      <button type="button" class="is-active" data-output-filter="all" aria-pressed="true">All</button>
      <button type="button" data-output-filter="presented" aria-pressed="false">Presented</button>
      <button type="button" data-output-filter="accepted" aria-pressed="false">Accepted</button>
      <button type="button" data-output-filter="review" aria-pressed="false">In review</button>
    </div>
  </div>

  <div class="outputs-grid" data-output-grid>
    {% for output in site.data.research_outputs %}
      <article class="output-card output-card--{{ output.stream }}{% if output.thumbnail %} output-card--has-poster{% endif %}" data-output-status="{{ output.status_key }}">
        {% if output.thumbnail %}
          <a class="output-card__visual output-card__visual--poster" href="{{ output.pdf }}" aria-label="Open {{ output.identifier }} poster PDF">
            <img src="{{ output.thumbnail }}" alt="" width="1400" height="788" loading="lazy">
            <span class="output-card__preview-label">View full poster</span>
          </a>
        {% else %}
          <div class="output-card__visual" aria-hidden="true">
            <span>{{ output.event_short }}</span>
            <strong>{{ output.identifier }}</strong>
            <i></i><i></i><i></i>
          </div>
        {% endif %}
        <div class="output-card__body">
          <div class="output-card__topline">
            <span class="status-pill status-pill--{{ output.status_key }}">{{ output.status }}</span>
            <span>{{ output.date }}</span>
          </div>
          <h2>{{ output.title }}</h2>
          <p class="output-card__authors">{{ output.authors }}</p>
          <div class="output-card__meta">
            <span>{{ output.event }}</span>
            <span>{{ output.location }}</span>
          </div>
          {% if output.pdf %}
            <a class="output-card__action" href="{{ output.pdf }}">Open poster PDF</a>
          {% elsif output.status_key == "presented" %}
            <span class="output-card__pending">Poster upload pending</span>
          {% endif %}
        </div>
      </article>
    {% endfor %}
  </div>
</section>

<section class="poster-cta">
  <p class="eyebrow">Living archive</p>
  <h2>Posters live here—not disappear after the conference.</h2>
  <p>Each ESMO AI card now opens a full-resolution PDF. Accepted SABCS work will move into the presented collection after the meeting; pending submissions stay clearly labeled until decisions arrive.</p>
</section>

<script>
  document.querySelectorAll('[data-output-filter]').forEach(function (button) {
    button.addEventListener('click', function () {
      var filter = button.getAttribute('data-output-filter');
      document.querySelectorAll('[data-output-filter]').forEach(function (item) {
        var active = item === button;
        item.classList.toggle('is-active', active);
        item.setAttribute('aria-pressed', active ? 'true' : 'false');
      });
      document.querySelectorAll('[data-output-status]').forEach(function (card) {
        card.hidden = filter !== 'all' && card.getAttribute('data-output-status') !== filter;
      });
    });
  });
</script>
