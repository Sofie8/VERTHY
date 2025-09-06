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

<!-- Logos side by side as big buttons -->
<div class="verthy-buttons">
  <a href="{{ '/env/' | relative_url }}" class="verthy-card">
    <img src="{{ '/images/VERTHY_ENV_ENG.png' | relative_url }}" alt="VERTHY ENV">
  </a>

  <a href="{{ '/ag/' | relative_url }}" class="verthy-card">
    <img src="{{ '/images/VERTHY_AG_ENG.png' | relative_url }}" alt="VERTHY AG">
  </a>
</div>

<style>
.verthy-buttons {
  display:flex;
  justify-content:center;
  gap:80px;
  margin:3rem 0;
  flex-wrap:wrap;
}

.verthy-card img {
  max-width:300px; /* Bigger logos */
  height:auto;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

/* Hover effect */
.verthy-card:hover img {
  transform: translateY(-8px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}
</style>

<!-- News section -->
{% include section.html %}

<h2 id="news">News</h2>
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color:#6b7280;"> — {{ post.date | date: "%d %b %Y" }}</span>
      {% if post.excerpt %}<div>{{ post.excerpt }}</div>{% endif %}
    </li>
  {% endfor %}
</ul>

<div class="center" style="margin-top:1rem;">
  {% include button.html
    link="news"
    title="All news"
    text="See all updates"
    icon="fas fa-newspaper"
    flip=true
    style="button"
  %}
</div>
