---
layout: post
---

{% for post in site.categories.life limit:1 %}

<div class="container">

<h3> {{ post.title }} </h3>

<div class="content">

{{ post.content }}

</div>

</div>

{% endfor %}
