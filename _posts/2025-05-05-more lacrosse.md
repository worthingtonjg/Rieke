---
layout: post
title: "More Lacrosse"
date: 2025-05-05
---

{% for photo in site.data["photos-20250505"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}