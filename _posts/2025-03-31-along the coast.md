---
layout: base
title: "Exploring Santa Cruz"
date: 2025-03-31
---

{% for photo in site.data["photos-20250331"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}