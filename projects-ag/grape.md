---
layout: page
title: Genetic screening for mildew resistance in grape
summary: "Cold-hardy vines with durable resistance: phenotyping, controlled inoculation, and marker-assisted screening."
hero: /images/minion.jpg
permalink: /projects-ag/mildew-grape/
---

<div class="project-card">
  <div class="project-hero">
    <img src="{{ page.hero | default: '/images/ag-mildew.jpg' | relative_url }}" alt="Powdery mildew resistance in grape">
  </div>

  <div class="project-body">
    <h1 class="project-title">{{ page.title }}</h1>
    <p class="project-subtitle">Breeding & selecting cold-hardy vines with durable resistance</p>

    <div class="pill-row">
      <span class="pill">Viticulture</span>
      <span class="pill">Resistance breeding</span>
      <span class="pill">NGS markers</span>
      <span class="pill">Field phenotyping</span>
    </div>

    <div class="two-col">
      <div>
        <h3>Overview</h3>
        <p>
          Powdery mildew is a key constraint in cool-climate viticulture. We connect field performance with
          genetic markers to identify vines with durable resistance while retaining quality traits.
        </p>

        <h3>What we do</h3>
        <ul>
          <li>Field phenotyping of grape collections in cold climates</li>
          <li>Controlled inoculations to benchmark resistance</li>
          <li>Marker-assisted screening of resistance loci (NGS)</li>
        </ul>
      </div>

      <div>
        <h3>Monitoring & verification</h3>
        <p>
          We monitor the <strong>degradation potential</strong> of microbial communities when relevant,
          screen the <strong>presence/activity of degradation genes</strong> after inoculation, and
          <strong>track introduced strains</strong> to confirm establishment and effect.
        </p>

        <h3>Outcomes</h3>
        <ul>
          <li>Shortlist of cold-hardy, mildew-resistant genotypes</li>
          <li>Marker sets linked to field resistance</li>
          <li>Scale-up plan: nursery validation → grower pilots</li>
        </ul>
      </div>
    </div>

    <div class="cta-row">
      <a class="btn" href="{{ '/projects-ag/' | relative_url }}"><i class="fas fa-arrow-left"></i> Back to AG projects</a>
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
  display:inline-flex; align-items:center; gap:.5rem; text-decoration:none;
  padding:.6rem .9rem; border-radius:10px; border:1px solid #e5e7eb; color:#0f172a;
  background:#fff; transition: all .2s ease;
}
.btn:hover{ transform: translateY(-2px); box-shadow:0 8px 20px rgba(0,0,0,.08); }
.btn.primary{ background:#217f82; color:#fff; border-color:#217f82; }
.btn.primary:hover{ background:#186c6d; border-color:#186c6d; }
</style>
