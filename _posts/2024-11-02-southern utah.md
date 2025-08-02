---
layout: base
title: "A Moab Adventure with AYUSA"
date: 2024-11-02
---

Today, Rieke set off on a new kind of adventure — a trip to Moab with Jen, the representative from the AYUSA exchange program. The goal was to give all the exchange students a chance to connect and experience one of Utah’s most iconic landscapes: Delicate Arch. At first, Rieke was a little hesitant about going. She didn’t know many of the other students and wasn’t sure what to expect, but we encouraged her to give it a shot — and we’re so glad she did.

The trip turned out to be a great experience. Surrounded by towering red rock and desert skies, Rieke not only got to hike to one of the most famous landmarks in the state, but also made new friends along the way. She came home tired, a little sunburned, but smiling — with stories, photos, and memories that helped her feel a little more connected to the wider exchange student community. It was one of those “only in Utah” experiences, and we were proud of her for jumping in.

{% for photo in site.data["photos-20241102"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}