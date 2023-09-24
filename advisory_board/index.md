---
title: Advisory
nav:
  order: 2
  tooltip: About our Advisory Board
---

# {% include icon.html icon="fa-solid fa-users" %}Advisory Board

<!-- Meet our advisors. -->

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: dinesh" %}
{% include list.html data="members" component="portrait" filters="role: jian" %}

{% include list.html data="members" component="portrait" filters="role: ab" %}

{% include section.html %}

{% capture content %}

<!-- {% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %} -->

{% endcapture %}

{% include grid.html style="square" content=content %}
