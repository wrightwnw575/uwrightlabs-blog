---
layout: default
title: Music
permalink: /music/
---

{% for song in site.music %}
## [{{ song.title }}]({{ song.url }})

{{ song.cover_image }}

{{ song.content | markdownify }}

---

{% endfor %}
