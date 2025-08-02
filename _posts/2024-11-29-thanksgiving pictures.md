---
layout: base
title: "Thanksgiving Pictures"
date: 2024-11-29
---

he day after Thanksgiving, we took advantage of the long weekend and beautiful weather to capture some family pictures — this time at the Provo Temple grounds. The air was crisp, but the sun was warm enough to make it a perfect fall day. The temple grounds were quiet and peaceful, with just enough golden leaves still clinging to the trees to give everything that late-autumn charm.

As with most family photo sessions, it took a little longer than expected — a lot of posing, adjusting, and waiting for everyone to smile at the same time. But it was worth it. We got some really lovely shots of Rieke with our family, and it felt meaningful to document this chapter with her included. These are the kinds of pictures that will end up in frames, on walls, and in Christmas cards — a reminder of how this year, our family grew by one, even if just for a season.

{% for photo in site.data["photos-20241129"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}