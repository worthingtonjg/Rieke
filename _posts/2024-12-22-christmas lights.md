---
layout: base
title: "Christmas Lights at the Aquarium"
date: 2024-12-22
---

{% for photo in site.data["photos-20241222"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}