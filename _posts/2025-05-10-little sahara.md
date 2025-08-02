---
layout: base
title: "The Little Sahara ~ Sand Dunes in Utah?"
date: 2025-05-10
---

{% for photo in site.data["photos-20250510"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}