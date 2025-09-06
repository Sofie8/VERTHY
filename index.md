---
layout: default
---

# Total Soil-utions, naturally!

<!-- Wide banner image -->
<img src="{{ '/images/startfoto.jpg' | relative_url }}" alt="VERTHY banner" style="width:100%; height:auto; margin: 1rem 0; border-radius:8px;">

<!-- Text block under image -->
<div style="max-width:800px; margin: 0 auto; text-align:left;">
 <p><strong>VERTHY</strong> provides expertise in soil consultancy, ecological remediation, and climate-smart agriculture. 
With us, you can rely on integrated soil analyses (CMA/ISO certified) and advice for the sustainable restoration of contaminated sites. 
We also offer specialist knowledge in plant and microbial genetics for agricultural applications (see <em>VERTHY AG</em>).

<p>We support you throughout the entire process — from initial feasibility tests, to field pilots and monitoring. 

<p>Click the buttons below to learn more about our projects and products, or choose “Who we are” to get to know our team.</p>

<!-- "Learn more about us" button -->
<div class="center" style="margin: 2rem 0;">
  {% include button.html
    link="about"
    title="Who we are"
    text="Learn more about us"
    icon="fas fa-arrow-right"
    flip=true
    style="button"
  %}
</div>

<!-- Logos side by side as big buttons -->
<div class="verthy-buttons">
<a href="{{ '/projects/' | relative_url }}" class="verthy-card">
  <img src="{{ '/images/VERTHY_ENV_ENG.png' | relative_url }}" alt="VERTHY ENV">
</a>

<a href="{{ '/projects-ag/' | relative_url }}" class="verthy-card">
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
  max-width:300px;
  height:auto;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

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
