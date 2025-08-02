---
layout: base
title: "Dance Peformance ~ Round 2"
date: 2025-05-13
---

{% for photo in site.data["photos-20250513"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}