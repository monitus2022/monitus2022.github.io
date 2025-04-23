---
layout: collection
title: "Page 1"
permalink: /1/
sidebar:
  nav: "docs"
---

## Testing 123

[Page 2]({{ site.baseurl }}/2/)
[Page 3]({{ site.baseurl }}/3/)

{% for post in paginator.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}

{% if paginator.next_page %}
  <a href="{{ paginator.next_page_path }}">Next</a>
{% endif %}