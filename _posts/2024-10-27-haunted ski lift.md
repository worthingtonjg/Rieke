---
layout: base
title: "Haunted Lifts and Halloween Chills"
date: 2024-10-27
---

To wrap up our magical Harry Potter weekend — and keep the Halloween spirit going strong — we headed to Sundance in the evening for one of the coolest (and creepiest) seasonal experiences around: the haunted ski lift. As the sun set behind the mountains and the air turned chilly, we boarded the lift and rose into the dark.

The ride itself was quiet and eerie, with just the hum of the cable and the occasional rustle of wind through the trees. Below us, scenes of glowing pumpkins, spooky lights, and creepy haunted vignettes played out on the forest floor. Even though the pictures didn’t turn out great — it’s tough to capture that kind of atmosphere — the experience itself was unforgettable. Suspended high in the dark, floating past ghosts, ghouls, and glowing scenes beneath the stars… it felt like we were flying through a Halloween storybook.

It was the perfect way to cap off a weekend of magic and memory-making.

{% for photo in site.data["photos-20241027"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}