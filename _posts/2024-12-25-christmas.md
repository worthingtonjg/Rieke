---
layout: post
title: "Christmas and the Grinch"
date: 2024-12-23
---

{% for photo in site.data["photos-20241225"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}