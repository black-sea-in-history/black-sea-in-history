---
title: cities
layout: default
---

<h2 class="text-2xl">Cities</h2>

<ul class="list-disc list-inside">
	{% for city in site.cities %}
		<li><a href="{{ city.url }}">{{city.name}}</a></li>
	{% endfor %}
</ul>
	
