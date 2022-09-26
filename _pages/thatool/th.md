---
layout: archive
title: "Note"
permalink: /notes/
author_profile: false
redirect_from:
  - /note
---

{% include base_path %}

<!-- include all .md files -->
{% for post in site.notes reversed %}
  {% include archive-single.html %}
{% endfor %}
