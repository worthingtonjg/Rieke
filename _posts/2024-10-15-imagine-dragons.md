---
layout: base
title: "Imagine Dragons at USANA"
date: 2024-10-15
---

Tonight was electric — we went to the USANA Amphitheatre to see Imagine Dragons live, and it ended up being one of the most memorable nights of Rieke’s stay so far. It was me, Jana, Molly, and Rieke, and we got there early enough to grab a good spot on the lawn. We spread out a blanket, took a few pre-show photos, and soaked in the vibe as the crowd slowly grew around us.

When Imagine Dragons finally took the stage, the entire place exploded with energy. Everyone jumped to their feet — and stayed there. For the rest of the night, we danced, sang along, and just let ourselves get carried away by the music. Rieke was all smiles, soaking up the full concert experience, and it felt like one of those pure moments of joy you wish you could bottle. Great music, a giant crowd, and a warm night under the stars — doesn’t get much better.

{% for photo in site.data["photos-20241015"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}