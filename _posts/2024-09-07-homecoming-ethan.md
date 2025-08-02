---
layout: base
title: "Homecoming with Ethan"
date: 2024-09-07
---

{% for photo in site.data["photos-20240907"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}