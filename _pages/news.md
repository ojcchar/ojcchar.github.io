---
title: "News"
permalink: /news/
author_profile: true
---

{% for item in site.data.news.main %}
 {{ forloop.index }}. ({{ item.date }}) {{ item.text }}
{% endfor %}