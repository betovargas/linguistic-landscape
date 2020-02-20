---
layout: archive
permalink: /about/
title: About
image:
    banner: ../images/torres-el-pez.jpg
---


*Linguistic Landscape*


<hr/>

## Contributors

*Spring 2020*

<div class="bios">
{% for member in site.data.members %}
	{% if member.year == 2019 %}
	{% include bioimg.html %}
	<div class="col-wide"><div id="title">{{ member.name }}</div> - {{ member.bio }}</div>
	{% endif %}
{% endfor %}
</div>

<hr/>

<div class="col-wide">
	<p><strong>Dr. Miranda Weinberg</strong>, Visiting Assistant Professor</p>
	<p><strong>Roberto Vargas</strong>, Research Librarian for Humanities and Interdisciplinary Studies</p>
	<hr/>
	<img src="../images/logo-mccabe-web.png" class="logo" alt="">
</div>

<hr/>