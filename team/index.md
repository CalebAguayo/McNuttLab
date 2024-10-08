---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab consists of a dynamic and collaborative group of researchers who are deeply engaged in their work. We understand that diverse teams produce superior research. We cultivate an environment where every team member is valued equally, and where our differences are respected and celebrated. Our team includes postdocs, students at all levels, staff, and our lab mascots.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: scientist, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: technician, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{% include section.html background="images/background.jpg" dark=true %}

We collaborate with an array of exceptional teams from across the globe and continually seek out fresh and unique perspectives. Our goal is to advance the frontiers of science and to mentor the next generation of scientists.

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="join"
  style="button"
%}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: scientist, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: technician, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: alum" style="small" %}

{% include section.html %}

## Funding

{% capture content %}

{%
  include figure.html
  image="images/Funding/nih logo.png"
  width="100%"
  height="100%"
  link= "https://www.nih.gov/"
%}
{%
  include figure.html
  image="images/Funding/DoD-Seal.png"
  width="100%"
  link= "https://www.defense.gov/"
%}
{%
  include figure.html
  image="images/Funding/DTRA-logo-FINAL-white.png"
  width="100%"
  link= "https://www.dtra.mil/"
%}

{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html %}