---
layout: default
title: Результаты курса ITMO "Веб-Технологии"
---

<h1>{{ page.title }} </h1>

<div id="blog-archives">

	{% for post in site.posts %}
        {% if post.type == "webtech" %}
            <article class="post">
                <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
            </article>
        {% endif %}
	{% endfor %}

</div>
