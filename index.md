---
---

{% capture text1 %}
VERTHY stands for consultancy in ecological site restoration, remediation and biotechnology. We design microbe- and plant-based solutions that detoxify polluted environments and promote sustainable crop growth. From DNA to field trials, I translate microbial ecology into practical tools for cleaner soils and sustainable agriculture.
{% endcapture %}

{% 
  include feature.html
  image="images/20220808_124510.jpg"
  title="Microbial Soilutions"
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

## Featured
{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More
{% include list.html component="card" data="projects" filter="!group" style="small" %}
