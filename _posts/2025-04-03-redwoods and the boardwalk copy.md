---
layout: base
title: "Redwoods and the Boardwalk"
date: 2025-04-03
---

{% for photo in site.data["photos-20250403"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}