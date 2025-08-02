---
layout: base
title: "Dress and Shoe Shopping"
date: 2024-08-24
---

{% for photo in site.data["photos-20240824"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}