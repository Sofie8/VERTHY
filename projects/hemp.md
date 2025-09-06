---
layout: page
title: PFAS Phytoremediation
summary: "Plant–microbe strategies to reduce PFAS in soils and crops."
hero: /images/hemp.jpg
permalink: /projects/pfas-phytoremediation/
---

<div class="project-card">
  <div class="project-hero">
    <img src="{{ page.hero | default: '/images/hemp.jpg' | relative_url }}" alt="PFAS Phytoremediation">
  </div>

  <div class="project-body">
    <h1 class="project-title">{{ page.title }}</h1>
    <p class="project-subtitle">Plant–microbe strategies to clean soils and safeguard crops</p>

    <div class="pill-row">
      <span class="pill">PFAS</span>
      <span class="pill">Phytoremediation</span>
      <span class="pill">Microbial inoculants</span>
      <span class="pill">qPCR & sequencing</span>
      <span class="pill">Scale-up</span>
    </div>

    <div class="two-col">
      <div>
        <h3>Overview</h3>
        <p>
          At VERTHY we explore <strong>plant–microbe strategies</strong> to lower PFAS levels in soils and crops.  
          Our work combines ecological knowledge with advanced molecular tools to design effective remediation pathways.
        </p>

        <h3>What we do</h3>
        <ul>
          <li>Screen <strong>plant genotypes</strong>, microbial <strong>inoculants</strong> and <strong>metabolites</strong>, and natural <strong>mineral amendments</strong>.</li>
          <li>Monitor microbial and plant responses using <strong>qPCR</strong>, <strong>amplicon/shotgun sequencing</strong>, and <strong>metabolomics</strong>.</li>
        </ul>
      </div>

      <div>
        <h3>Expected outcomes</h3>
        <ul>
          <li><strong>Reduced PFAS uptake</strong> in crops.</li>
          <li><strong>Enhanced degradation pathways</strong> through optimized plant–microbe interactions.</li>
          <li>A <strong>clear scale-up plan</strong> for field implementation.</li>
        </ul>

        <p>
          This project brings together laboratory innovation and practical field testing, 
          with the goal of making contaminated soils safer and supporting sustainable land use.
        </p>
      </div>
    </div>

    <div class="cta-row">
      <a class="btn" href="{{ '/projects/' | relative_url }}"><i class="fas fa-arrow-left"></i> Back to ENV projects</a>
      <a class="btn primary" href="{{ '/contact' | relative_url }}"><i class="fas fa-envelope"></i> Contact us</a>
    </div>
  </div>
</div>

<style>
.project-card{
  max-width: 980px; margin: 0 auto 2.5rem; background:#fff;
  border:1px solid #e5e7eb; border-radius:16px; overflow:hidden;
  box-shadow: 0 6px 24px rgba(0,0,0,.06);
}
.project-hero img{ width:100%; height: 320px; object-fit: cover; display:block; }
.project-body{ padding: 1.25rem 1.5rem 1.75rem; }
.project-title{ margin: .2rem 0 0; font-size: 1.9rem; }
.project-subtitle{ color:#64748b; margin: .25rem 0 1rem; }

.pill-row{ display:flex; flex-wrap:wrap; gap:.5rem; margin-bottom:1.25rem; }
.pill{
  background:#e6f4f4; color:#217f82; padding:.25rem .6rem; border-radius:999px;
  font-size:.85rem; border:1px solid #cde7e7;
}

.two-col{ display:grid; grid-template-columns: 1fr; gap:1.25rem; }
.two-col h3{ margin:.5rem 0 .35rem; }
.two-col p{ margin:.25rem 0 .5rem; }
.two-col ul{ margin:.25rem 0 .5rem 1rem; }
@media (min-width: 860px){
  .two-col{ grid-template-columns: 1fr 1fr; gap:1.5rem 2rem; }
  .project-hero img{ height: 380px; }
}

.cta-row{ display:flex; gap:.75rem; flex-wrap:wrap; margin-top:1.25rem; }
.btn{
  display:inline-flex; align-items
