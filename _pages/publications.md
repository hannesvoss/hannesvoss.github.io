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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* A. Schmitz et al.: Introduction of MONOCLE - a software to reduce the workload and optimize the processes of the molecular tumor board at the University Hospital Hamburg-Eppendorf, https://doi.org/10.3205/23gmds068.
* R. Schmitz et al.: 3D- and surface reconstruction of endoluminal resection specimens from sparse and deformed histologic tissue sections from routine clinical specimens, to be submitted.