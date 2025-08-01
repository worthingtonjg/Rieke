---
layout: post
title: "Hiking the Payson P"
date: 2024-10-21
---

{% for photo in site.data["photos-20241021"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}