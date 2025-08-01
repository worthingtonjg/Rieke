---
layout: post
title: "Corn Bellies"
date: 2024-10-04
---

{% for photo in site.data["photos-20241004"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}