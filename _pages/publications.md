---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

* auto-gen TOC:
{:toc}

First-author publications
------

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

All publications
-------

You can find all my publications via [this ADS search](https://ui.adsabs.harvard.edu/search/filter_property_fq_property=AND&filter_property_fq_property=property%3A%22refereed%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq=%7B!type%3Daqp%20v%3D%24fq_property%7D&fq_database=(database%3Aastronomy%20OR%20database%3Aphysics)&fq_property=(property%3A%22refereed%22)&q=orcid%3A0000-0002-5945-7975&sort=date%20desc%2C%20bibcode%20desc&p_=0).

Thesis
-------

You can find my thesis [at this link](https://theses.fr/2019AIXM0317)