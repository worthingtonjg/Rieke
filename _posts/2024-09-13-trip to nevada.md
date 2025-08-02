---
layout: base
title: "Nevada and Bonneville Salt Flats"
date: 2024-09-13
---

{% for photo in site.data["photos-20240913"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}