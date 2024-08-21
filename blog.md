---
layout: default
title: "Blog"
---

# Blog

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
*Pubblicato il {{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}
{% endfor %}
