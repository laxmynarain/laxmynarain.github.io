---
layout: page
title: Resume
---

# Lakshminarayanan Sadagopan

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
you can [get the PDF]({{ site.url }}{{ site.baseurl }}/assets/mydoc.pdf) directly.
