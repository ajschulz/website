---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{%
  include button.html
  type="email"
  text="ajs692@cornell.edu"
  link="ajs692@cornell.edu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/PAG_talk.JPG"
  caption="Presenting reelGene at PAG 2024"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/harvest.jpg"
  caption="Out in the research field"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}

{% endcapture %}

{% capture col2 %}

{% endcapture %}

{% capture col3 %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
