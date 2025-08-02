---
layout: base
title: "Shopping with Addie"
date: 2025-01-18
---

If there’s one thing Rieke never said no to, it was a shopping trip — especially if her partner-in-style, Addie, was coming along. These two could turn a quick run to the store into a full-blown fashion adventure. On one of their many outings, they stumbled across a rack of faux fur coats, and of course, had to try them on. A few dramatic poses later, they were looking straight out of a fashion magazine — or at least they thought so, and honestly, we did too.

They may not have taken the coats home, but the pictures (and the laughs) were definitely keepers. Just another reminder that with the right friend, even window shopping turns into a memory.

{% for photo in site.data["photos-20250118"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}