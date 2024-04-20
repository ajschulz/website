---
title: About Me
nav:
  order: 3
  tooltip: About Aimee
---

# {% include icon.html icon="fa-solid fa-users" %}About Me

Test info here

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: PhD Candidate" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/headshot.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
