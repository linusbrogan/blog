---
layout: home
---

# Blog posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
