---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from: 
  - /wordpress/academic-papers/
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?view_op=search_authors&mauthors=lizeth+tamayo&hl=en&oi=ao">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.articles reversed %}
  {% include archive-single.html %}
{% endfor %}


