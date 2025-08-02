---
layout: base
title: "More Lacrosse"
date: 2025-05-05
---

Lacrosse season is winding down, and each game feels a little more meaningful as we get closer to the end. Rieke has come such a long way since those first practices on the field — from nervous beginner to confident defender (and even a goal scorer!).

Today’s game was another solid showing. The team played hard, and Rieke held her own on defense like she always does, giving it her all. There’s a bittersweet feeling in the air now — the season’s almost over, and while it’s been exhausting at times, it’s also been one of the highlights of her school year. We’re just proud to be on the sidelines, cheering her on every step of the way.

{% for photo in site.data["photos-20250505"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}