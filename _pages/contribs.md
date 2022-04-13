---
layout: archive
title: "Contribs"
permalink: /contribs/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Presentations

{% for post in site.presentations reversed %}
  {% include archive-single.html %}
{% endfor %}
