---
layout: page
title: PFAS Phytoremediation
summary: |
  by VERTHY | June -AUG 2025 | Phytoremediation | Beveren-Kruibeke-Zwijndrecht<br>
  Plant–microbe strategies to reduce the spread of PFAS in soils.
hero: /images/hemp.jpg
permalink: /projects/pfas-phytoremediation/
---

<div class="project-card">
  <div class="project-hero">
    <img src="{{ page.hero | default: '/images/hemp.jpg' | relative_url }}" alt="PFAS Phytoremediation">
  </div>

  <div class="project-body">
    <h1 class="project-title">{{ page.title }}</h1>

    <!-- Subtitle (meta line under title) -->
    {% if page.subtitle %}
      <p class="project-meta">{{ page.subtitle }}</p>
    {% endif %}

    <p class="project-subtitle">Plant–microbe strategies to clean soils</p>

    <div class="pill-row">
      <span class="pill">PFAS</span>
      <span class="pill">Phytoremediation</span>
      <span class="pill">Scale-up</span>
    </div>

    <div class="two-col">
      <div>
        <h3>Overview</h3>
        <p>
          This 3-hectare site, owned by a project developer, lies at the heart of a <strong>PFAS risk area</strong> due to its proximity to former firefighting
          training grounds and nearby industrial activities, which have caused PFOS and PFOA contamination in both the topsoil and groundwater. At the same time,
          we are at the border of nature and agriculture. This unique region, surrounded by nature, agriculture, and industry, offers both challenges and
          opportunities to integrate these seemingly dual objectives of expanding economic activities and ensuring a healthy living environment. Using nature
          based solutions, like <strong>phytoremediation</strong>, we aim to mitigate pollution risks of further PFAS spreading while simultaneously enhancing
          biodiversity within the region. In this way, <strong>remediation and ecological management reinforce one another</strong>, while still allowing space
          for redevelopment and the economic ambitions of the project developer.
        </p>

        <h3>What we did</h3>
        <ul>
          <li>Screened <strong>hemp genotypes for fast growth and root development</strong>, collected <strong>soil and plant samples</strong>.</li>
          <li>Monitored responses using <strong>PFAS soil analyses</strong> and <strong>PFAS plant analyses</strong>.</li>
        </ul>
      </div>

      <div>
        <h3>Outcomes</h3>
        <ul>
          <li><strong>4–95% reductions</strong> in PFAS concentrations in the top soil.</li>
          <li><strong>Reduced PFAS spread from topsoil</strong> through stabilization by 3 million hemp plants.</li>
          <li>A <strong>clear scale-up plan</strong> shown with successful field implementation.</li>
        </ul>

        <!-- Results figure -->
        <figure class="results-figure">
          <img src="{{ '/images/ZABRA1.png' | relative_url }}" alt="PFAS results">
          <figcaption>
            Remediation and ecological site restoration at a PFAS risk area with industrial hemp.
          </figcaption>
        </figure>

        <p style="margin-top:0.8rem;">
          This project ties desktop work with practical field testing to make contaminated soils cleaner and safer, 
          supporting sustainable land use, hand in hand with site redevelopment and economic valorization.
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
.project-hero img{
  width:100%; height: 340px; object-fit: cover; object-position: center; display:block;
}
@media (min-width: 1024px){
  .project-hero img{ height: 420px; }
}
.project-body{ padding: 1.25rem 1.5rem 1.75rem; }
.project-title{ margin: .2rem 0 0; font-size: 1.9rem; }

/* Meta subtitle just under title */
.project-meta{ color:#64748b; font-size:0.95rem; margin:0.2rem 0 0.8rem; }

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
  max-width: 420px;
  margin: 1rem auto;
  border-radius: 10px;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;  /* centers image + caption */
}
.results-figure img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 10px;
}
.results-figure figcaption {
  font-size: 0.85rem;
  color: #64748b;
  margin-top: 0.4rem;
  text-align: center;
}
</style>
