---
layout: archive
title: "Talks & Posters"
permalink: /presentations/
author_profile: true
---


{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}


{% for post in site.posters reversed %}
  {% include posters-single.html %}
  afsdasgasd
  ---
{% endfor %}
