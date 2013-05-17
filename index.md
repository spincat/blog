---
layout: post
---

{% for post in site.categories.life %}

<div class="container">

<h3> {{ post.title }} </h3>

<div class="content">

{{ post.content }}

</div>

</div>

{% endfor %}
