---
---

{% capture text1 %}
I’m Sofie Thijs, a molecular microbiologist working at the nexus of plants, soils, and their microbiomes. I design microbe- and plant-based solutions that detoxify polluted environments and make crops more resilient. From DNA to field trials, I translate microbial ecology into practical tools for cleaner soils and sustainable agriculture.
{% endcapture %}

{% 
  include feature.html
  image="images/who.jpg"
  title="Who I am"
  text=text1
  link="about"
%}

<div class="center">
  {%
    include button.html
    link="about"
    title="Who I am"
    text="Learn more about me"
    icon="fas fa-arrow-right"
    flip=true
    style="button"
  %}
</div>

{% include section.html %}

{% 
  include feature.html
  image="images/projects.PNG"
  title="What I do"
  text=text2
  link="projects"
  flip=true
%}

{% capture text2 %}
- **Soil** — diagnose soil health, pollutants, and stressors; co-design nature-based remediation strategies.
- **Plants** — select plants for phytoremediation and climate-smart growth; test seed and foliar interventions
- **Bacteria & Fungi** — isolate, engineer and assemble microbial consortia for **growth promotion**, **biocontrol**, and **pollutant degradation**.
- **From lab to field** — End-to-end workflows (feasibility → pilots → field validation according to the code of good practice phytoremediation) to reduce pollutant loads (incl. **PFAS**) and restore function.
{% endcapture %}

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

