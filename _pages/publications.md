---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my most up-to-date publication list at <u><a href="https://scholar.google.com/citations?hl=en&user=crAyusoAAAAJ&view_op=list_works&sortby=pubdate">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
