---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my publications on <u><a target="_blank" href="{{site.author.googlescholar}}">Google Scholar</a></u> and <u><a target="_blank" href="{{site.author.dblp}}">DBLP</a></u>.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
