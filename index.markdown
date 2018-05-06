---
layout: default
title: Home
---

## joeriks - coding in the cloud

{% for post in site.categories[page.category] %}
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>    
{% endfor %}
