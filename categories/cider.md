---
layout: category
title: Ciders
permalink: '/categories/cider.html'
---

## Blog Posts

{% for post in site.categories['cider'] %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
