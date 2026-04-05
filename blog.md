---
layout: default
title:  My Blog
---

# Blog Posts

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
<p>{{ post.excerpt }}</p>
{% endfor %}
