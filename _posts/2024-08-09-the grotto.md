---
layout: post
title: "The Grotto and Karate"
date: 2024-08-09
---

{% for photo in site.data["photos-20240809"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}