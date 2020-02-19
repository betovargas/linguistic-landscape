---
layout: front
permalink: /
title: home
image:
    banner: images/linguistic-landscape.jpg
---

<div class="tiles">

{% for post in site.posts %}
{% include post-grid.html %}
{% endfor %}

</div>
