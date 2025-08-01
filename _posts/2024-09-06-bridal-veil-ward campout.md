---
layout: post
title: "Ward Campout"
date: 2024-09-06
---

{% for photo in site.data["photos-20240902"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}