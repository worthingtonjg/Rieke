---
layout: base
title: "Bridal Viel Falls and Bike Ride"
date: 2024-09-02
---

{% for photo in site.data["photos-20240902"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}