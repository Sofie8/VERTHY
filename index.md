---
---

{% capture text1 %}
I’m Sofie Thijs, a molecular microbiologist working at the nexus of plants, soils, and their microbiomes. I design microbe- and plant-based solutions that detoxify polluted environments and make crops more resilient. From DNA to field trials, I translate microbial ecology into practical tools for cleaner soils and sustainable agriculture.
{% endcapture %}

{% 
  include feature.html
  image="images/who.jpg"
  title="Who I am"
  text=I try to see and explain nature’s complexity—then turn it into solutions for healthy soils and resilient crops.
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

{% capture text2 %}
I am a creative, forward-thinking and passionist biologist & data-analyst. I pursued a bachelors degree in Biology at Hasselt University, followed by a masters in Environmental Health Sciences. During my PhD (2015), I isolated a bacterium called, Raoultella ornithinolytica strain TNT and discovered its potential to 'eat' and detoxify the explosive, TNT (trinitrotoluene). I described it's genome, overexpressed the degradation gene N-ethylmaleimide reductase (NEM), purified the protein, and showed that NEM has nitroreductase activity toward TNT with kinetic properties comparable to the PETN-reductase from Enterobacter cloacae.

As a postdoc in the Neufeld Lab (University of Waterloo, Canada) I helped develop GORDIAN—a genome-resolved density-gradient workflow to recover high-quality draft genomes from complex metagenomes—while deepening my bioinformatics expertise. 

Now, as postdoc-coördinator (UHasselt), I lead applied microbiome projects that connect genomics, metabolomics, and field trials. I work on PFAS phytoremediation (PLANTS) and a microbial toolbox for pollution remediation (MIBIREM). I develop and co-develop analysis tools (e.g. MANANAS, an R-shiny pipeline for microbiome data analyses) and test seed treatments, foliar applications of microbes/metabolites, and natural soil minerals to modulate pollutant uptake.
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
    text="My projects"
    icon="fas fa-arrow-right"
    flip=true
    style="button"
  %}
</div>

