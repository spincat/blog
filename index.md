---
layout: post
---

{% for post in site.categories.life %}

<div class="container">
## {{ post.title }}

<div class="content">

{{ post.content }}

</div>

</div>