---
layout: base
title: "Imagine Dragons"
date: 2024-10-15
---

{% for photo in site.data["photos-20241015"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}