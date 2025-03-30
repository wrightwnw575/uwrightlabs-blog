---
layout: default
title: Blog
permalink: /blog/
---

{% for post in site.blog %}
## [{{ post.title }}]({{ post.url }})

{{ post.excerpt }}

---

{% endfor %}
