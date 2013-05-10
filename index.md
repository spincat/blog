---
layout: post
---

{% for post in paginator.posts %}
{% if forloop.index == 1 %}
	<div class="container">
	<div class="title"><a href="{{ post.url }}">{{ post.title }}</a></div>
	<div class="date">记于{{ post.date | date:"%Y年%m月%d日"}} <a href="/categories/#{{ post.categories }}">{{ post.categories }}</a></div>
	<div class="content">
	{{ post.content }}
	</div>
{% endif %}
{% endfor %}