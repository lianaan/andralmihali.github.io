---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true

---

![image](https://github.com/lianaan/andralmihali.github.io/blob/master/images/fig1intrE.png)(: .align-left "width=300px")


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=P652FREAAAAJ&hl=en&oi=ao}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
