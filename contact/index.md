---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

# We welcome motivated postdoctoral researchers, graduate students, and undergraduates to join the team！


{%
  include button.html
  type="email"
  text="shuojunli@fudan.edu.cn"
  link="shuojunli@fudan.edu.cn"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/c1.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/c2.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

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

{% include section.html dark=true %}

{% capture col1 %}
<p>
Room C321, School of Life Sciences, Fudan University<br>
2005 Songhu Rd, Yangpu District<br>
Shanghai 200438, China<br><br>
上海市杨浦区淞沪路2005号<br>
复旦大学江湾校区生命科学学院 C321
</p>
{% endcapture %}

{% capture col2 %}
{% endcapture %}

{% capture col3 %}
{% endcapture %}

{% include cols.html col1=col1 %}
