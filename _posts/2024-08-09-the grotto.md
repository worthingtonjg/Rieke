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

<div class="day-nav-float">
  {% if page.previous %}
    <a href="{{ page.previous.url | relative_url }}">← {{ page.previous.title }}</a>
  {% endif %}
  {% if page.next %}
    <br/><a href="{{ page.next.url | relative_url }}">{{ page.next.title }} →</a>
  {% endif %}
</div>