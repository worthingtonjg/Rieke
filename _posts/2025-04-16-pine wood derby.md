---
layout: base
title: "Pine Wood Derby"
date: 2025-04-16
---

{% for photo in site.data["photos-20250416"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}