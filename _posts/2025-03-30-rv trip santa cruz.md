---
layout: base
title: "RV trip in Santa Cruz"
date: 2025-03-30
---

{% for photo in site.data["photos-20250330"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}