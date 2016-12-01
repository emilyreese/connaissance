<!-- ---
layout: page
title: Archive
permalink: /archive/
---

(or go back to browsing [individually]({{ site.baseurl }}/))

***
{% for post in site.posts %}
  [ {{ post.title }} ]({{ post.url | prepend: site.baseurl }})
  {{ post.content }}
  ***
{% endfor %}
 -->
