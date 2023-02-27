---
layout: default
title: Результаты курса ITMO "Веб-Технологии"
---

<h1>{{ page.title }} </h1>

<div id="blog-archives">

	{% for webtech in site.webtechs %}
		<article class="post">
            <h1><a href="{{ webtech.url }}">{{ webtech.title }}</a></h1>
		</article>
	{% endfor %}

</div>
