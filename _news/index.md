---
title: Whats New
layout: news
hide: true
permalink: /news/index
---

{% for item in site.news %}
    {% if item.isCurrent and item.hide != true %}
{{ item.content }}
    {% endif %}
{% endfor %}