---
layout: post
title: "Southern Utah"
date: 2024-11-02
---

{% for photo in site.data["photos-20241102"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}