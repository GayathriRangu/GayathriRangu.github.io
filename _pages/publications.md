---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
page_theme: publications
background_image: bg-ai-robotics-subtle.jpg
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
