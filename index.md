---
title: What is Truth?
description: "Pontius Pilate asked Jesus Christ 'What is Truth' (John 18:38)\nEach of us must ask this question."
---

## Posts
Posts count: {{ site.posts | size }}

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

{% endfor %}
