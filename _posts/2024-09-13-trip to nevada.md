---
layout: base
title: "Road Trip to Nevada (with a Salty Surprise)"
date: 2024-09-13
---

Today we packed up the car for a road trip to Minden, Nevada to visit Jana’s dad. The drive took us west across the I-80 — which, if you’ve ever driven it, you know is one of the most mind-numbing stretches of highway in the country. Miles and miles of open desert, endless sagebrush, and not much else. But even boring road trips have their moments, and ours came with a salty twist.

The Bonneville Salt Flats were our saving grace. We pulled off to stretch our legs and ended up spending way longer than planned, wandering out across the blinding white landscape. It felt like stepping onto another planet — flat, bright, and stretching forever in every direction. Rieke loved it, snapping photos and goofing around with Molly and Ryan. It’s not every day you can walk barefoot on salt in the middle of nowhere and call it a highlight, but it definitely was. The road trip rolled on, but that stop made the whole drive worth it.

{% for photo in site.data["photos-20240913"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}