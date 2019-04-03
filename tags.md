---
layout: page
title: Tags
permalink: /tags/
sitemap:
  priority: 1.0
---
{% for tag in site.tags %}
* [{{ tag.name }}]({{ site.baseurl }}/tags/{{ tag.name }})
{% endfor %}

