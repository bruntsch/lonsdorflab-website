---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Interested in joining the lab? Want to collaborate with us? Any questions regarding our research? Feel free to contact us!

{%
  include button.html
  type="email"
  text="sekretariat-ae14@uni-bielefeld.de"
  link="sekretariat-ae14@uni-bielefeld.de"
%}
{%
  include button.html
  type="phone"
  text="+49-521-106-4482"
  link="+49-521-106-4482"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Bielefeld+University/@52.0367271,8.4926664,17z/data=!3m2!4b1!5s0x47ba980fd0e9d4bb:0x2cc7502b92aebcec!4m6!3m5!1s0x47ba22b5ad10b98f:0xa128cd4b4ccac32d!8m2!3d52.0367238!4d8.4952413!16zL20vMDU5YmJj?entry=ttu&g_ep=EgoyMDI1MDIwOS4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/events/team1.jpg"
  caption="PUG 2025"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/events/team2.jpg"
  caption="EMHFC 2025"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}