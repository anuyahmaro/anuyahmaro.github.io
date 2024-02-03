---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[//]: # ({ if author.googlescholar })
  You can also find my articles on my <u><a href="https://scholar.google.com/citations?user=8mv5WeEAAAAJ&hl=en">Google Scholar</a></u> and <u><a href="https://www.researchgate.net/profile/Oghenemaro-Anuyah">ResearchGate</a></u> profiles.

[//]: # ({ endif })
<h2>Major Peer-reviewed Conference and Journals</h3>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

