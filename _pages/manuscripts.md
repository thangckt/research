---
layout: archive
title: "publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}


## Manuscripts

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

