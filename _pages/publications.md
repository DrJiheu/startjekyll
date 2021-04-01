---
title: "Alexandra Palacio Morales - Publications"
layout: gridlay
excerpt: "Alexandra Palacio Morales -- Publications."
sitemap: false
permalink: /publications/
---


# Publications



(For a full list see [below](#full-list) or go to [Publons](https://publons.com/researcher/2243867/alexandra-palacio-morales/))
{% for year in site.data.years %}
  <strong>{{ year.year }}</strong>
	{% for publi in site.data.publist %}
		{% if publi.year == year.year%}
  {{ publi.title }} <br /> <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
		{% endif %} 
	{% endfor %}
{% endfor %}