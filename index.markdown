---
layout: default
title: Home
---

[About](/about/) · [Portfolio](/portfolio/)

## Posts

{% for post in site.posts %}
- {{ post.date | date: "%b %-d, %Y" }} &mdash; [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
