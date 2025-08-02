---
layout: base
title: "Christmas Cheer and a Night to Dance"
date: 2024-12-14
---

Today was full of holiday spirit and sparkle. We kicked things off at our ward Christmas party — the kind of gathering that brings everyone together over warm food, festive decorations, and plenty of cheer. After dinner, the youth groups took to the stage. Rieke joined the Young Women and sang Christmas songs with the rest of the teens — a sweet little performance that made the whole room smile. It was one of those simple, cozy holiday moments that make December feel special.

But the night wasn’t over yet. After the party, Rieke went home to change into full glam mode — makeup, curls, and a fancy dress — because tonight was also a school dance. She and her friend Addie took pre-dance photos, striking all the confident, stylish poses like seasoned pros. They looked fantastic and headed out ready to dance the night away. From ward stage to school spotlight, Rieke made the most of her December Saturday — festive, fabulous, and full of fun.

{% for photo in site.data["photos-20241214"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}