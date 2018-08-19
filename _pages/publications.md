---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
 You can also find my articles/abstracts at <u><a href="https://scholar.google.co.il/citations?user=JEF9QWQAAAAJ&hl=en">Google Scholar</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
