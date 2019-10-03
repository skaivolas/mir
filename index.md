---
title: Галоўная
layout: home
published: true
---


<ul>
  {% for post in site.posts reversed %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li> 
{% endfor %}
</ul>
