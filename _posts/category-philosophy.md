---
title: "Philosophy Posts"
layout: page
permalink: /category/philosophy/
---

## Philosophy  

{% for post in site.categories.philosophy %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
