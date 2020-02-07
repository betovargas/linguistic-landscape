---
layout: front
permalink: /
title: home
image:
    banner: images/linguistic-landscape.jpg
---
### Fall of 2019

<div class="tiles">
{% for member in site.data.members %}
   {% if member.year == 2019 %}
   {% include post-grid.html %}
   {% endif %}
{% endfor %}
</div>
<hr/>


Linguistic landscape project

<hr/>
