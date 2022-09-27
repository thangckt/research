---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<br>
## Publications:

{% if site.author.googlescholar %}
  Articles in <a href="{{site.author.googlescholar}}" style="text-decoration:none">my Google Scholar profile</a>.
{% endif %}

{% if site.author.orcid %}
  Articles in <a href="{{site.author.orcid}}" style="text-decoration:none">my ORCID profile</a>.
{% endif %}


{% for post in site.publications reversed %}
  {% include archive-single-paper.html %}
{% endfor %}


<br>
## Manuscripts:

{% for post in site.manuscripts reversed %}
  {% include archive-single-paper.html %}
{% endfor %}