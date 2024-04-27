---
layout: archive
title: "Publications"
collection: publications
permalink: /publications/
excerpt: ' <br/><img src='/images/fig1intrE.png' '
author_profile: true

---



{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=P652FREAAAAJ&hl=en&oi=ao}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
