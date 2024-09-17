---
layout: archive
title: "Contribs 學術貢獻"
permalink: /contribs/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Publications 學術著作

{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}

## Presentations 口頭報告

{% for post in site.presentations reversed %}
  {% include presentation.html %}
{% endfor %}
