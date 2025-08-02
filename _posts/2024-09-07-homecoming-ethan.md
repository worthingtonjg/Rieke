---
layout: base
title: "Homecoming Magic"
date: 2024-09-07
---

Homecoming finally arrived, and Rieke was absolutely glowing. From the moment she found her dress, she'd been counting down the days, and tonight was everything she hoped it would be — getting dressed up, taking pictures, and heading out for a true American high school dance. The boy? His name was Ethan. He seemed nice enough, and more importantly, he had his own car — a definite plus in Rieke’s book.

But honestly, the boy was just a small part of the night. For Rieke, the real excitement was all the other pieces: curling her hair, putting on makeup with Jana’s help, posing for pictures, and heading out to join a crowd of classmates in suits and sparkly dresses. Watching her leave with a huge smile and a little nervous energy, we couldn’t help but feel proud. She was fully diving into this experience, one dance and awkward group photo at a time.

{% for photo in site.data["photos-20240907"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}