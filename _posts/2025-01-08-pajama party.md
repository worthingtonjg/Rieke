---
layout: post
title: "Young Women ~ Pajama Party"
date: 2025-01-08
---

{% for photo in site.data["photos-20250108"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}