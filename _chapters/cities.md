---
title: Cities
leaflet: true
---

<div id="map" class="w-full" style="height: 40vh;">

<ul class="list-disc list-inside">
	{% for city in site.cities %}
		<li><a href="{{ city.url | prepend: site.baseurl }}">{{city.name}}</a></li>
	{% endfor %}
</ul>
	
