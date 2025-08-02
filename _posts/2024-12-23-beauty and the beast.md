---
layout: base
title: "Beauty and the Beast at Hale Center Theatre"
date: 2024-12-23
---

{% for photo in site.data["photos-20241223"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}