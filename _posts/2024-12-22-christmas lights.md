---
layout: base
title: "Christmas Lights at the Aquarium"
date: 2024-12-22
---

With Christmas just around the corner, we bundled up and headed to the Loveland Living Planet Aquarium for their outdoor Christmas light display — and it was far from ordinary. Sure, there were the classic twinkling trees and glowing snowflakes, but what made this display special was the way it brought the animal kingdom to life in lights.

We wandered past glowing polar bears, penguins, jellyfish, butterflies, and more — each display more creative and colorful than the last. The cold nipped at our noses, but it didn’t take away from the fun. Rieke loved spotting all the different animals, and we took our time strolling through, laughing, pointing things out, and snapping photos whenever our fingers weren’t frozen. It was a magical mix of holiday spirit and nature’s wonder — the kind of night that makes the season feel alive.

{% for photo in site.data["photos-20241222"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}