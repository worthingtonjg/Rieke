---
layout: base
title: "Lacrosse ~ She scores!"
date: 2025-04-14
---

{% for photo in site.data["photos-20250414"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}