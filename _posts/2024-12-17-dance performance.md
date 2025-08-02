---
layout: base
title: "School Dance Peformance"
date: 2024-12-17
---

{% for photo in site.data["photos-20241217"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}