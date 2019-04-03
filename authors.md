---
layout: page
title: Authors
permalink: /authors/
sitemap:
  priority: 1.0
---
{% for author in site.authors %}
* [{{ author.name }}]({{ site.baseurl }}/authors/{{ author.name }})
{% endfor %}
