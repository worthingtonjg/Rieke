---
layout: base
title: "Chruch ~ Matchies"
date: 2025-04-13
---

{% for photo in site.data["photos-20250413"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}