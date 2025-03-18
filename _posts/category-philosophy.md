---
title: "Philosophy Posts"
layout: default
---

## Philosophy  

{% for post in site.categories.philosophy %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
