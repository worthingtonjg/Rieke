---
layout: base
title: "Shopping with Addie"
date: 2025-01-18
---

{% for photo in site.data["photos-20250118"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}