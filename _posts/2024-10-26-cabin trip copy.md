---
layout: base
title: "A Very Harry Potter Cabin Weekend"
date: 2024-10-26
---

This weekend was our annual fall cabin trip — something we look forward to every year as the leaves turn and the air gets crisp. This time, we went all in with a theme: Harry Potter. We packed up and headed up Provo Canyon, surrounded by golden trees and cool mountain air, ready for a weekend of magic.

What makes this trip truly special every year is Mema. She plans the entire weekend from start to finish — choosing the theme, crafting the decorations by hand, and coming up with games and activities that fit the theme perfectly. She poured so much love into the details: floating candles, potion bottles, chocolate frogs, and even a sorting ceremony. The cabin was transformed thanks to her creativity, and we’re always blown away by the care and joy she puts into making it magical for everyone.

Everyone chose their house (some more competitively than others), and we leaned into the fun with trivia, butterbeer, and cozy robes. Rieke jumped right in — she may not have grown up with Harry Potter in the same way, but she loved the atmosphere, the fun, and the excuse to fully nerd out with the rest of us. It was the perfect way to enjoy fall, spend time together, and add a little magic to the mountains.

{% for photo in site.data["photos-20241026"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}