---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: false
---

{% include base_path %}

<!-- include all .md files -->
{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
