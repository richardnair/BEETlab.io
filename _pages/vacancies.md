---
title: "News"
layout: textlay
excerpt: "PSF Group at Trinity College Dublin."
sitemap: false
permalink: /allnews.html
---

# Vacancies
<h1 id="open-positions">Open positions</h1>

*We are currently advertising the following vacancies:*

{% for article in site.data.jobs %}
{{ article.title }} <br> {{ article.description | markdownify}}
{% endfor %}


