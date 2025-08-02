---
layout: base
title: "Hoover Dam and Vegas"
date: 2024-09-30
---

{% for photo in site.data["photos-20240930"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}