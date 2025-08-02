---
layout: base
title: "Timpanogos Cave"
date: 2024-09-22
---

{% for photo in site.data["photos-20240922"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}