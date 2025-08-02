---
layout: base
title: "Santaquin Rodeo"
date: 2024-08-03
---

{% for photo in site.data["photos-20240803"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}

