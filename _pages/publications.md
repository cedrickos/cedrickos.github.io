---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
  ul.a {
    list-style-type: disk;
  }
</style>

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

You can also find my articles on:
<ul class="a">
  <li>
    {% if author.googlescholar %}
      <a href="{{author.googlescholar}}">Google Scholar</a>.
    {% endif %}
  </li>
  <li>
    {% if author.researchgate %}
      <a href="{{author.researchgate}}">ResearchGate</a>.
    {% endif %}
  </li>
</ul>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
