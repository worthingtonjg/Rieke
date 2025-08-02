---
layout: base
title: "Surf, Sand, and a Cold Pacific Welcome"
date: 2025-03-31
---

On our second day along the coast, we left the RV park and set out to explore the beaches around Santa Cruz and Monterey Bay. The sky was still a little gray, but that didn’t stop us from kicking off our shoes and walking barefoot through the sand. The cold Pacific Ocean lapped at our feet — icy, refreshing, and a little shocking — but part of the full California experience.

We stopped at a lighthouse that had been turned into a surf-themed gift shop, full of quirky beach decor and local surf history. After browsing a bit, we spent time just sitting near the shore, watching real surfers catch waves in the chilly water. It was mesmerizing — the rhythm of the ocean, the quiet skill of the surfers, and the steady roar of the waves.

By the time we got back to the KOA, we still had enough energy (somehow) for one more dip in the pool and a few more bounces on the giant pillow. It was one of those simple, perfect days — beachy, breezy, and unforgettable.

{% for photo in site.data["photos-20250331"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}