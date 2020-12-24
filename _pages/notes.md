---
layout: page
title: Notes
id: notes
permalink: /notes
---

# All Notes on New Wander! 🌱
<!-- 
<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Your first note]]</span> to get started on your exploration.
</p> -->



{% for note in site.notes %}

  <a href="{{ note.url }}">{{ note.title }}</a>

{% endfor %}
