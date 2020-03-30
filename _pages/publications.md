---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on:

{% if author.googlescholar %}
  <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% if author.researchgate %}
  <u><a href="{{author.researchgate}}">my ResearchGate profile</a>.</u>
{% endif %}

{% if author.orcid %}
  <u><a href="{{author.orcid}}">my ORCid profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
