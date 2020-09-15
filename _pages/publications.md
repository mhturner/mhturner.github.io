---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

To see up-to-date info, see my  <u><a href="{{ author.googlescholar }}" target="_blank">Google Scholar profile</a>.</u>

{% for post in site.publications reversed %}
  {% include publication-single.html %}
  ---
{% endfor %}
