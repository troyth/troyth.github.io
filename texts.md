---
layout: page
title: Texts
---
{% for text in site.texts %}
	<div class="text">
		<h2><a href="{{ text.url }}">{{ text.title }}</a></h2>
	</div>
{% endfor %}
