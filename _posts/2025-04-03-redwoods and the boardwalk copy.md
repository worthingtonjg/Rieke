---
layout: base
title: "Redwoods and the Boardwalk"
date: 2025-04-03
---

For the final day of our California adventure, we made one last unforgettable stop — the redwoods. We drove north to explore the towering trees, and no matter how many pictures you’ve seen, nothing compares to walking beneath them in person. The air was cool and quiet, and the trees stretched so high it felt like we were in a cathedral built by nature. It was humbling and grand all at once — the kind of place that makes you feel small in the best way.

After our time among the giants, we made a lighter, livelier stop at the boardwalk. The classic California seaside vibe was in full swing — roller coasters, snack stands, and the smell of saltwater in the air. It was the perfect contrast to the peaceful forest we’d just left. A little bit of awe, a little bit of fun, and a perfect way to end the trip.

{% for photo in site.data["photos-20250403"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}