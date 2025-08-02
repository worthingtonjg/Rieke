---
layout: base
title: "Pine Wood Derby"
date: 2025-04-16
---

Our ward held its annual Pinewood Derby, and this year I decided to go all in and build not one, but two cars — one for Rieke and one for Molly. Rieke’s car, naturally, was pink, sleek, and built for speed. Molly's, on the other hand, was pure attitude: a glittery purple nod to Mad Max, complete with sparkles and just the right amount of imaginary firepower.

The girls had an absolute blast racing their cars down the track with the rest of the ward. Neither of them took home the championship trophy, but both cars held their own — easily finishing in the top 25%. More importantly, they laughed, cheered, and beamed with pride as their creations flew down the track. It was a night full of friendly competition, sawdust, and a lot of pink and purple power.

{% for photo in site.data["photos-20250416"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}