---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: false
---

{% include base_path %}

<!-- include all .md files -->
{% for post in site.notes reversed %}
  {% include archive-single.html %}
{% endfor %}
