---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Questions, collaborations, or project requests? We’d love to hear from you.

{%
  include button.html
  type="email"
  text="verthycv@gmail.com"
  link="verthycv@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="(0032) 498534052"
  link="+32-498-53-40-52"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo1.jpg"
  caption=""
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
When the problem’s in the ground,
the answer is too —
microbial soil-utions.
{% endcapture %}

{% capture col2 %}
I try to see and explain nature’s complexity
then turn it into solutions
for healthy soils and
resilient crops.
{% endcapture %}

{% capture col3 %}
To solve environmental challenges,
we must first become students of nature.
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
