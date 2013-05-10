---
layout: post
---

{% for post in site.categories.blog %}
  {{ post.title }}			
  {{ post.description }}
  {{ post.content }}
{% endfor %}