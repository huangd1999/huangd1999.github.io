---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{[site.author.googlescholar](https://scholar.google.com/citations?user=UER9hrAAAAAJ&hl=en)}}">my Google Scholar profile</a>.</div>
{% endif %}

{% bibliography %}


<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
