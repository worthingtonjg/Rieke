---
layout: post
title: "Skiing at Eagle Point"
date: 2025-02-07
---

{% for photo in site.data["photos-20250207"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}