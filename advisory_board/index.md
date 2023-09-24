---
title: Advisory
nav:
  order: 2
  tooltip: About our Advisory Board
---

# {% include icon.html icon="fa-solid fa-users" %}Advisory Board

Meet our PIs.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: ab" %}


{% include section.html background="images/background.jpg" dark=true %}

<!-- Meet our team members. -->

{% include section.html %}

<!-- {% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %} -->

{% capture content %}

<!-- {% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %} -->

{% include grid.html style="square" content=content %}
