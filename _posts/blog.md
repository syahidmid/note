---
layout: default
title: Blog
permalink: /blog/
---
# Blog

{% for post in site.blog %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}
