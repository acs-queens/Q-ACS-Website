---
title: Team
nav:
  order: 2
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: president" %}
{% include list.html data="members" component="portrait" filters="role: treasurer" %}
{% include list.html data="members" component="portrait" filters="role: secretary" %}
{% include list.html data="members" component="portrait" filters="role: public-outreach-director" %}
{% include list.html data="members" component="portrait" filters="role: events-director" %}
{% include list.html data="members" component="portrait" filters="role: social-media-director" %}
{% include list.html data="members" component="portrait" filters="role: faculty-advisor" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include grid.html style="square" content=content %}
