---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet our PIs.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}


{% include section.html background="images/background.jpg" dark=true %}

Meet our team members.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% capture content %}

<!-- {% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %} -->

{% endcapture %}

{% include grid.html style="square" content=content %}
