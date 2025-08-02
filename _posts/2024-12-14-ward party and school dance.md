---
layout: base
title: "Ward Christmas Party and School Dance with Addie"
date: 2024-12-14
---

{% for photo in site.data["photos-20241214"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}