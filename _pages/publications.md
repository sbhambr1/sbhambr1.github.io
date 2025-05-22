---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can find an updated list of articles on <u><a href="https://scholar.google.co.in/citations?user=E9I6GbwAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
