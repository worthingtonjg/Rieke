---
layout: base
title: "Dance Peformance ~ Round 2"
date: 2025-05-13
---

Tonight was Rieke’s end-of-year dance performance — her second big show of the year, and a beautiful way to close out the season. This time, the dancers wore striking red dresses, and Rieke once again lit up the stage with confidence and grace.

It’s been amazing watching her grow through these performances — not just in skill, but in presence. She moved with such poise and energy, you could tell she was fully in the moment. We were proud (again!) to be in the audience, cheering her on as she wrapped up another chapter of her American adventure on a high note.

{% for photo in site.data["photos-20250513"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}