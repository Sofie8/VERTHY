---
layout: default
---

{% capture text1 %}
VERTHY offers expertise in soil, ecology, and genetics.  
With us you can rely on:

- **Integrated soil analyses and advice** for ecological site restoration.  
- **Genetic analyses** of plants and microbes for sustainable agriculture.  
- **Support from lab to field**: from DNA studies and pilot tests to monitoring full-scale projects.  

Our mission is to turn science into practical tools for cleaner soils and resilient crops.  
Click below to explore our products or meet our team.
{% endcapture %}

{% include feature.html
  image="images/startfoto.jpg"
  title="Total Soil-utions, naturally!"
  text=text1
  link="about"
%}

<div class="center">
  {% include button.html
    link="about"
    title="Who we are"
    text="Learn more about us"
    icon="fas fa-arrow-right"
    flip=true
    style="button"
  %}
</div>

{% include section.html %}

<!-- Two clickable logo tiles -->
<div style="display:grid; grid-template-columns: 1fr; gap:24px; align-items:center; justify-items:center; margin: 2rem 0;">
  <a href="{{ '/env/' | relative_url }}" style="text-align:center; text-decoration:none;">
    <img src="{{ '/images/verthy-env.png' | relative_url }}" alt="VERTHY ENV" style="max-width:220px; height:auto;">
    <div style="font-weight:700; font-size:1.4rem; color:#2a9ea0; margin-top:0.5rem;">VERTHY ENV</div>
    <div style="color:#5a7f86;">Ecological remediation</div>
  </a>

  <a href="{{ '/ag/' | relative_url }}" style="text-align:center; text-decoration:none;">
    <img src="{{ '/images/verthy-ag.png' | relative_url }}" alt="VERTHY AG" style="max-width:220px; height:auto;">
    <div style="font-weight:700; font-size:1.4rem; color:#2a9ea0; margin-top:0.5rem;">VERTHY AG</div>
    <div style="color:#5a7f86;">Engineering Nature</div>
  </a>
</div>

<style>
@media (min-width: 700px){
  .page-content > div[style*="grid-template-columns"]{
    grid-template-columns: 1fr 1fr !important;
  }
}
a:hover img { transform: translateY(-2px); transition: 150ms; }
</style>

{% include section.html %}

<!-- News section -->
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

