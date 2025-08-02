---
layout: base
title: "Bye Bye Teddy"
date: 2025-05-21
---

{% for photo in site.data["photos-20250521"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}