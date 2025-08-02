---
layout: base
title: "Missionary Month"
date: 2025-03-05
---

{% for photo in site.data["photos-20250305"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}