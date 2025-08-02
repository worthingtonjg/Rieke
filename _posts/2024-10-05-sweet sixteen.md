---
layout: base
title: "Sweet Sixteen"
date: 2024-10-05
---

{% for photo in site.data["photos-20241005"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}