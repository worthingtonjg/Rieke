---
layout: base
title: "Young Women ~ Pajama Party"
date: 2025-01-08
---

This morning, the Young Women in our ward hosted a pajama party princess breakfast — and it was exactly as fun and whimsical as it sounds. Rieke joined the other girls decked out in their comfiest PJs, ready for a morning of food, laughter, and just a little sparkle.

{% for photo in site.data["photos-20250108"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}