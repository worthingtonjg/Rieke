---
layout: base
title: "Sweet Sixteen"
date: 2024-10-05
---

Rieke's birthday technically happened the week before, on September 27th, while we were down at Lake Mead — and we did celebrate there — but she had her heart set on a real party with her new friends from the tennis team. So tonight, we threw her the kind of birthday she’d really been hoping for: a princess-themed pajama party.

While we were in Vegas, we picked up a sparkly tiara just for the occasion, and Jana surprised her with a silky pink pajama set from Victoria’s Secret. Unfortunately, the excitement took a slight hit when Rieke accidentally burned a hole in the pants while ironing them. She was pretty upset, but she pulled herself together like a champ and decided not to let it ruin the night.

The house was full of laughter, snacks, and birthday energy as her tennis teammates showed up in their PJs, ready for games, pictures, and all things pink and sparkly. It was the kind of party that marked not just a birthday, but the growing friendships and memories she was starting to build here — tiara and all.

{% for photo in site.data["photos-20241005"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}