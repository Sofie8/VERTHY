---
---

{% capture text1 %}
We are a young dynamic team delivering innovative solutions at the intersection of biotechnology and nature based solutions for sustainable remediation.
{% endcapture %}

{% 
  include feature.html
  image="images/who.jpg"
  title="Who we are"
  text=text1
  link="about"
%}

<div class="center">
  {%
    include button.html
    link="about"
    title="Who we are"
    text="Learn more about us"
    icon="fas fa-arrow-right"
    flip=true
    style="button"
  %}
</div>

{% include section.html %}

{% capture text2 %}
We support soil remediation experts, agricultural professionals and individuals by translating ideas and experimental data into actionable solutions for environmental remediation, sustainable agriculture, and microbe-based solutions.
{% endcapture %}

{% 
  include feature.html
  image="images/projects.PNG"
  title="What we do"
  text=text2
  link="projects"
  flip=true
%}

<div class="center">
  {%
    include button.html
    link="projects"
    text="Our projects"
    icon="fas fa-arrow-right"
    flip=true
    style="button"
  %}
</div>

