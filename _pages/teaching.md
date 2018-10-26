---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

I have been Teaching Assistant for the following courses at The University of Texas at Dallas (UTD):

{% for post in site.teaching reversed %}
  {% include teaching-single.html %}
{% endfor %}
