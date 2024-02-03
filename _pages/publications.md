---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{ if author.googlescholar }
  You can also find my articles on my <u><a href="{{author.googlescholar}}">Google Scholar</a></u> and <u><a href="{{author.researchgate}}">ResearchGate</a></u> profiles.
{ endif }

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
<h1>Major Peer-reviewed Conference and Journals</h1>
