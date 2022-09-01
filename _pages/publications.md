---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Broadly, my research interests include the impacts of physical oceanography on species distributions and how these bio-physical interactions may drive marine species biogeography, food webs, and ecological interactions. While my dissertation focused on a biological hotspot in the Antarctic, I am interested in answering these types of questions in a variety of ecosystems, using a combination of in-situ observations, physical ocean models, and ecological modeling techniques. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
