---
layout: base
title: "Corn Bellies"
date: 2024-10-04
---

October rolled in, and with it came the start of one of our favorite seasons — fall festivals and haunted corn mazes. Tonight we headed up to Cornbelly’s at Thanksgiving Point, a tradition for many Utah families this time of year. Mema joined us for the night (she surprised us with tickets — thanks, Mema!), and we packed in as much fun as we could.

While Molly and Rieke weren’t exactly eager to brave the haunted houses, they had a blast with everything else — wandering through the corn mazes, diving into the corn pit, racing through obstacle courses, and flying down giant slides. We snacked on popcorn, shared caramel apples, and soaked up the crisp fall air and glowing string lights. It was one of those perfectly simple nights that makes October feel like magic — just a bunch of laughter, warm treats, and shoes full of corn kernels.

{% for photo in site.data["photos-20241004"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}