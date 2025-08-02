---
layout: post
title: "Gingerbread Cookies"
date: 2024-12-12
---

{% for photo in site.data["photos-20241212"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}