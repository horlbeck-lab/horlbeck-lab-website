---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# Team

We are always looking to grow our team. We are looking for teammates of all scientific and personal backgrounds who are interested in making discoveries in basic science, improving the lives of children with rare disease, and building a collaborative and fun community. {%
  include button.html
  link="contact/#join-us"
  text="Join us!"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and group != 'alum'" %}


{% include section.html %}
<!-- 
{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %} -->

{% include grid.html style="square" content=content %}
