---
layout: post
title: "Fire Fighter Breakfast"
date: 2025-05-26
---

{% for photo in site.data["photos-20250526"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}