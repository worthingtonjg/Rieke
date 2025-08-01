---
layout: post
title: "Thanksgiving Pictures"
date: 2024-11-29
---

{% for photo in site.data["photos-20241129"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}