---
title: ENV Projects
nav:
  order: 2
  tooltip: Our environmental projects
---

# {% include icon.html icon="fa-solid fa-leaf" %} VERTHY ENVIRONMENT

At VERTHY ENVIRONMENT we work on ecological remediation and soil improvement by combining plant, microbe and data-driven approaches.  
Below you’ll find an overview of our main project lines, core services and featured use-cases.

## Projects at a glance

- **Phytoremediation feasibility studies and success control monitoring**  
  We assess the degradation potential of microbial communities on site through eDNA sampling. This includes detecting the presence and activity of degradation genes before and after inoculation using next-generation sequencing techniques, and tracking the fate of introduced strains to ensure they establish and contribute to pollutant breakdown.

- **PFAS phytoremediation**  
  Phytoextraction, phytostabilisation and phytohydraulics strategies to reduce the risk of PFAS spreading in soils and groundwater: screening plant species and genotypes, mineral amendments to reduce or enhance uptake, microbial inoculants/metabolites. Monitoring via soil biology, analytics, plant-uptake, nutrient and soil type analyses, metagenomics, and metabolomics.

- **Data & monitoring pipelines**  
  **MANANAS** (R-shiny) for amplicon/shotgun analysis, custom qPCR assays, and reproducible reporting dashboards that link **genomes → traits → field performance**.

{% include section.html %}

## Core services

- Site diagnostics & sampling plans
- Phytoremediation feasibility assessments   
- Molecular monitoring (qPCR, amplicon/shotgun, metabolomics)  
- Pilot design: plant–microbe interventions  
- Bacterial inoculum development  
- Success-control monitoring  

*The best way to understand our work is to browse example projects.*

{% include section.html %}

# Featured projects

<div class="proj-grid">
  {% assign pages = site.pages | where_exp: "p","p.path contains 'projects/'" %}
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
