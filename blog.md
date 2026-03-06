---
layout: page
title: Blog
permalink: /blog/
---

Short posts about my academic work, projects, and things I’m learning.

{% raw %}{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}{% endraw %}
