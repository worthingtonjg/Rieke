---
layout: base
title: "Hoover Dam and Vegas"
date: 2024-09-30
---

On the way home from our Lake Mead weekend, we decided to turn the return trip into an adventure of its own. First stop: the Hoover Dam. Even though we’ve been before, it’s still an impressive sight — massive, iconic, and a little dizzying when you’re standing at the top looking straight down. Rieke was fascinated by both the scale and the story behind it, and we took a guided tour inside to see the tunnels, generators, and the engineering marvel that holds back Lake Mead. She kept saying it felt like something out of a movie.

From there, we made a quick detour into Las Vegas for the full glitz-and-glamour drive down the Strip. We didn’t stay long, but we cruised past the neon lights, pointing out all the over-the-top themed hotels. We stopped at Excalibur and Luxor to snap a few photos — castles and pyramids right in the middle of the desert. It was the perfect mix of history and spectacle, and a great way to end an already unforgettable trip.

{% for photo in site.data["photos-20240930"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}