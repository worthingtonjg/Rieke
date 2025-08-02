---
layout: base
title: "Relaxing at the KOA"
date: 2025-04-02
---

{% for photo in site.data["photos-20250402"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}