---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

We run projects from  PFAS phytoremediation, microbiome engineering, bacterial genetics and genetic marker screening for downy-mildew resistance in climate-smart grape vine breeding.

---
{% capture text2 %}
- **Soil** — diagnose soil health, pollutants, and stressors; co-design nature-based remediation strategies.
- **Plants** — select plants for phytoremediation and climate-smart growth; test seed and foliar interventions
- **Bacteria & Fungi** — isolate, engineer and assemble microbial consortia for **growth promotion**, **biocontrol**, and **pollutant degradation**.
- **From lab to field** — End-to-end workflows (feasibility → pilots → field validation according to the code of good practice phytoremediation) to reduce pollutant loads (incl. **PFAS**) and restore function.
{% endcapture %}

{% 
  include feature.html
  image="images/Project.png"
  title="What I do"
  text=text2
  link="projects"
  flip=true
%}


<div class="center">
  {%
    include button.html
    link="projects"
    text="My projects"
    icon="fas fa-arrow-right"
    flip=true
    style="button"
  %}
</div>


## Projects we run (at a glance)

- **PFAS phytoremediation**  
  Plant–microbe strategies to lower PFAS in soils and crops: screening plant genotypes, microbial inoculants/metabolites, and mineral amendments to reduce uptake or enhance degradation. Monitoring via soil analytics, plant-uptake, nutrient and soil type analyses, metagenomics, and metabolomics.

- **Powdery mildew resistance in cold climate**  
  Breeding and selecting cold-hardy vines with durable resistance: field phenotyping, controlled inoculation, and marker screening of resistance loci using NGS.

- **Microbiome engineering for sustainable agriculture**  
  Genome mining, plasmidomics, and metabolomics to uncover traits for plant growth promotion, biocontrol, and pollutant degradation. Bench-to-field workflows (seed and foliar treatments, formulation, and success-control metrics).

- **Data & monitoring pipelines**  
  **MANANAS** (R-shiny) for amplicon/shotgun analysis, custom qPCR assays, and reproducible reporting dashboards that link **genomes → traits → field performance**.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured
{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More
{% include list.html component="card" data="projects" filter="!group" style="small" %}
