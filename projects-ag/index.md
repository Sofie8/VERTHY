---
title: AG Projects
nav:
  order: 3
  tooltip: Our agricultural projects
permalink: /projects-ag/
---

# {% include icon.html icon="fa-solid fa-seedling" %} VERTHY AG Projects

At VERTHY AG we combine plant and microbial genetics with field experience to develop practical solutions for sustainable agriculture.  
We focus on improving crop resilience, supporting farmers with innovative inoculants, and translating molecular insights into real-world benefits.

## Projects at a glance

- **Powdery mildew resistance in cold climate**  
  Breeding and selecting cold-hardy vines with durable resistance: field phenotyping, controlled inoculation, and marker screening of resistance loci using NGS.

- **Microbiome engineering for sustainable agriculture**  
  Genome mining, plasmidomics, and metabolomics to uncover traits for plant growth promotion, biocontrol, and pollutant degradation. Bench-to-field workflows (seed and foliar treatments, formulation, and success-control metrics).

{% include section.html %}

## Core services

- Genetic screening of plant resistance traits  
- Microbial inoculant and metabolite development  
- Field pilot design for seed and foliar treatments  
- Microbial community monitoring (qPCR, sequencing)  
- Linking genotype → phenotype → field performance  

*The best way to understand our work is to browse example projects.*

{% include section.html %}

# Featured projects

<div class="proj-grid">
  {% assign pages = site.pages | where_exp: "p","p.path contains 'projects-ag/'" %}
  {% for p in pages %}
    {% if p.url != page.url %}
      <a class="proj-card" href="{{ p.url | relative_url }}">
        {% if p.hero %}<img src="{{ p.hero | relative_url }}" alt="{{ p.title }}">{% endif %}
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
