---
title: Contact
nav:
  order: 5
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{%
  include button.html
  type="email"
  text="sscacs@queensu.ca"
  link="sscacs@queensu.ca"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/90+Bader+Ln,+Kingston,+ON+K7L+2S8/@44.2245989,-76.5014032,17z/data=!3m1!4b1!4m6!3m5!1s0x4cd2ab1b278b40d5:0x9e0f37b09ae97725!8m2!3d44.2245951!4d-76.4988283!16s%2Fg%2F11c2hr977h?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/chernoff_hall.jpeg"
  caption="Chernoff Hall, the home of Queen's University's Department of Chemistry and Q-ACS"
%}

{% endcapture %}

{% include cols.html col1=col1 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
