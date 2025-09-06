---
layout: page
title: Test Project Card
subtitle: by VERTHY | 2025 | Test Location
summary: "A very simple test card."
hero: /images/minion.jpg
permalink: /projects-ag/test-card/
---

<div class="project-card">
  <div class="project-body">
    <h1 class="project-title">{{ page.title }}</h1>

    <!-- Meta subtitle -->
    {% if page.subtitle %}
      <p class="project-meta">{{ page.subtitle }}</p>
    {% endif %}

    <p class="project-subtitle">This is a test to check if the subtitle renders.</p>
  </div>
</div>

<style>
.project-card{
  max-width: 600px; margin: 2rem auto; background:#fff;
  border:1px solid #e5e7eb; border-radius:10px; padding:1rem;
  box-shadow: 0 4px 12px rgba(0,0,0,.06);
}
.project-title{ font-size: 1.5rem; margin:0; }
.project-meta{ color:#64748b; font-size:0.95rem; margin:0.3rem 0 1rem; }
.project-subtitle{ color:#475569; font-size:1.1rem; }
</style>
