---
layout: default
---

# Total Soil-utions, naturally!

<!-- Wide banner image -->
<img src="{{ '/images/startfoto.jpg' | relative_url }}" alt="VERTHY banner" style="width:100%; height:auto; margin: 1rem 0; border-radius:8px;">

<!-- Text block under image -->
<div style="max-width:800px; margin: 0 auto; text-align:left;">
  <p><strong>VERTHY</strong> offers expertise in soil, ecology, and genetics.</p>

  <p>With us you can rely on:</p>
  <ul>
    <li><strong>Integrated soil analyses and advice</strong> for ecological site restoration.</li>
    <li><strong>Genetic analyses</strong> of plants and microbes for sustainable agriculture.</li>
    <li><strong>Support from lab to field:</strong> from DNA studies and pilot tests to monitoring full-scale projects.</li>
  </ul>

  <p>Our mission is to turn science into practical tools for cleaner soils and resilient crops.</p>
</div>

<!-- Buttons side by side -->
<div class="verthy-buttons">
  <a href="{{ '/env/' | relative_url }}" class="verthy-card">
    <img src="{{ '/images/VERTHY_ENV_ENG.png' | relative_url }}" alt="VERTHY ENV">
    <div class="title">VERTHY ENV</div>
    <div class="subtitle">Ecological remediation</div>
  </a>

  <a href="{{ '/ag/' | relative_url }}" class="verthy-card">
    <img src="{{ '/images/verthy-ag.png' | relative_url }}" alt="VERTHY AG">
    <div class="title">VERTHY_AG_ENG</div>
    <div class="subtitle">Engineering Nature</div>
  </a>
</div>

<style>
.verthy-buttons {
  display:flex;
  justify-content:center;
  gap:40px;
  margin:2rem 0;
  flex-wrap:wrap;
}

.verthy-card {
  text-align:center;
  text-decoration:none;
  transition: all 0.25s ease;
}

.verthy-card img {
  max-width:200px;
  height:auto;
  transition: transform 0.25s ease;
}

.verthy-card .title {
  font-weight:700;
  font-size:1.2rem;
  color:#2a9ea0;
  margin-top:0.5rem;
  transition: color 0.25s ease;
}

.verthy-card .subtitle {
  color:#5a7f86;
  transition: color 0.25s ease;
}

/* Hover effect */
.verthy-card:hover img {
  transform: translateY(-6px);
}

.verthy-card:hover .title {
  color:#186c6d;
}

.verthy-card:hover .subtitle {
  color:#2a9ea0;
}
</style>

