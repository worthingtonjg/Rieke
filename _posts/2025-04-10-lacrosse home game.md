---
layout: base
title: "Lacrosse - Another home game"
date: 2025-04-10
---

{% for photo in site.data["photos-20250410"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}