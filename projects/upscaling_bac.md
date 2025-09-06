---
layout: page
title: Upscaling bacterial inocula for remediation
subtitle: VERTHY | 2025 | Melsbroek | Plant–microbe | Phytoremediation
summary: "From lab to field — upscaling and delivering of microbes as allies for plants."
hero: /images/inoc.jpg
permalink: /projects/upscaling/
---

<div class="project-card">
  <div class="project-hero">
    <img src="{{ page.hero | default: '/images/inoc.jpg' | relative_url }}" alt="Upscaling bacterial inocula for remediation">
  </div>

  <div class="project-body">
    <h1 class="project-title">{{ page.title }}</h1>

    <!-- Subtitle -->
    {% if page.subtitle %}
      <p class="project-meta">{{ page.subtitle }}</p>
    {% endif %}

    <p class="project-subtitle">Translating microbial strains into reliable, field-ready products</p>

    <div class="pill-row">
      <span class="pill">Plant–microbe</span>
      <span class="pill">Pollutant degradation & PGP</span>
      <span class="pill">Bioreactor</span>
      <span class="pill">Field pilots</span>
    </div>

    <div class="two-col">
      <div>
        <h3>Overview</h3>
        <p>
          Soil, rhizospheric and endophytic bacteria can boost pollutant degradation.
          We identify, validate, and scale microbial functions that improve pollutant detoxification.
          By enhancing their expression, we accelerate phytoremediation and expand nature’s own detoxification capacity.
          For this project, we upscaled an oil- and PAH-degrading bacterial inoculum to tackle a kerosene oil spill,
          demonstrating how targeted microbial consortia can boost both remediation efficiency and plant resilience. 
        </p>

        <h3>What we did</h3>
        <ul>
          <li><strong>Bacterial genome mining & plasmidomics</strong> to discover functional traits (PGP, degradation, biocontrol).</li>
          <li><strong>Metabolite screening</strong> to profile active degradation, mode of action and transformation products.</li>
          <li><strong>Bench → field workflows</strong>: soil drench inocula formulation, upscaling and stability testing.</li>
        </ul>
      </div>

      <div>
        <h3>Monitoring & verification</h3>
        <p>
          We track the <strong>growth-promotion and degradation potential</strong> of microbial communities,
          assess the <strong>presence and activity of target genes</strong> after inoculation (qPCR, amplicon/shotgun),
          and <strong>follow introduced strains</strong> to confirm establishment and field impact.
        </p>

        <h3>Outcomes</h3>
        <ul>
          <li>Shortlist of robust strains or consortia with validated field performance.</li>
          <li>Formulation and <em>success-control</em> metrics for reliable on-site use.</li>
          <li>Scale-up plan: pilot design → grower trials → productization.</li>
        </ul>

        <!-- Results figure -->
        <figure class="results-figure">
          <img src="{{ '/images/inoculant.png' | relative_url }}" alt="Upscaling workflow results">
          <figcaption>
            Example workflow: from genome mining to field validation.
          </figcaption>
        </figure>
      </div>
    </div>

    <div class="cta-row">
      <a class="btn" href="{{ '/projects/' | relative_url }}"><i class="fas fa-arrow-left"></i> Back to ENV projects</a>
      <a class="btn primary" href="{{ '/contact' | relative_url }}"><i class="fas fa-envelope"></i> Contact us</a>
    </div>

    <!-- Learn more reference -->
    <div style="text-align:center; margin-top:2rem; font-size:0.9rem; color:#64748b;">
      Would you like to learn more? Visit 
      <a href="https://www.frontiersin.org/journals/microbiology" target="_blank">Frontiers in Microbiology</a>.
    </div>
  </div>
</div>

<style>
.project-card{
  max-width: 980px; margin: 0 auto 2.5rem; background:#fff;
  border:1px solid #e5e7eb; border-radius:16px; overflow:hidden;
  box-shadow: 0 6px 24px rgba(0,0,0,.06);
}
.project-hero img{
  width:100%; height: 340px; object-fit: cover; object-position: center; display:block;
}
@media (min-width: 1024px){
  .project-hero img{ height: 420px; }
}
.project-body{ padding: 1.25rem 1.5rem 1.75rem; }
.project-title{ margin: .2rem 0 0; font-size: 1.9rem; }

/* Subtitle style */
.project-meta{ color:#64748b; font-size:0.95rem; margin:0.25rem 0 1rem; }

.project-subtitle{ color:#475569; margin: .25rem 0 1rem; font-size:1.1rem; }

.pill-row{ display:flex; flex-wrap:wrap; gap:.5rem; margin-bottom:1.25rem; }
.pill{
  background:#e6f4f4; color:#217f82; padding:.25rem .6rem; border-radius:999px;
  font-size:.85rem; border:1px solid #cde7e7;
}

.two-col{ display:grid; grid-template-columns: 1fr; gap:1.25rem; }
@media (min-width: 860px){
  .two-col{ grid-template-columns: 1fr 1fr; gap:1.5rem 2rem; }
}

.cta-row{ display:flex; gap:.75rem; flex-wrap:wrap; margin-top:1.25rem; }
.btn{
  display:inline-flex; align-items:center; gap:.5rem; text-decoration:none;
  padding:.6rem .9rem; border-radius:10px; border:1px solid #e5e7eb; color:#0f172a;
  background:#fff; transition: all .2s ease;
}
.btn:hover{ transform: translateY(-2px); box-shadow:0 8px 20px rgba(0,0,0,.08); }
.btn.primary{ background:#217f82; color:#fff; border-color:#217f82; }
.btn.primary:hover{ background:#186c6d; border-color:#186c6d; }

/* Results figure styling */
.results-figure {
  max-width: 320px;
  margin: 1rem auto;
  border-radius: 10px;
  text-align: center;
}
.results-figure img {
  display: block;
  width: 50%;
  height: auto;
  border-radius: 10px;
}
.results-figure figcaption {
  font-size: 0.85rem;
  color: #64748b;
  margin-top: 0.4rem;
}
</style>
