---
layout: default
title: Hello World!
---
{% for post in site.posts %}

<article>
	<header>
		<h2><a href=".{{ post.url }}">{{ post.title }}</a></h2>
		<p>{{ post.date | date_to_string }}</p>
	</header>
	{{ post.content }}
</article>

{% endfor %}
