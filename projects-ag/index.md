---
layout: page
title: VERTHY AG Projects
permalink: /projects-ag/
---

Below you’ll find a selection of our agriculture projects.  
We focus on plant & microbial genetics, field trials, and bioproducts.

<div class="proj-grid">
  {% assign pages = site.pages | where_exp: "p","p.path contains 'projects-ag/'" %}
  {% for p in pages %}
    {% if p.url != page.url %}
      <a class="proj-card" href="{{ p.url | relative_url }}">
        {% if p.hero %}
          <img src="{{ p.hero | relative_url }}" alt="{{ p.title }}">
        {% endif %}
        <div class="proj-title">{{ p.title }}</div>
        {% if p.summary %}<div class="proj-summary">{{ p.summary }}</div>{% endif %}
      </a>
    {% endif %}
  {% endfor %}
</div>

<style>
.proj-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:20px;margin-top:1rem}
.proj-card{text-decoration:none;border:1px solid #e5e7eb;border-radius:10px;overflow:hidden;background:#fff;transition:.2s}
.proj-card:hover{transform:translateY(-4px);box-shadow:0 10px 20px rgba(0,0,0,.08)}
.proj-card img{width:100%;height:160px;object-fit:cover}
.proj-title{font-weight:700;color:#217f82;padding:.6rem .8rem}
.proj-summary{color:#6b7280;padding:0 .8rem 1rem}
</style>

