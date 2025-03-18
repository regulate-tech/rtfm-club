---
layout: default
title: Posts
permalink: /posts/
---

### Blog Posts

{% for post in site.posts %}
  * {{ post.date | date: "%Y-%m-%d" }} - [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}