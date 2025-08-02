---
layout: base
title: "Chruch ~ Matchies"
date: 2025-04-13
---

Church is a big part of our weekly rhythm — from Wednesday night youth activities to Sunday sacrament meeting and Sunday school. It’s a time to slow down, connect, and focus on the things that matter most. Rieke has really embraced this part of our life, always showing up with a smile (and usually a great outfit, too).

This particular Sunday, we all had a good laugh when we realized we’d accidentally coordinated — every one of us showed up dressed in blue. No planning, no group text, just one of those weird and funny coincidences that make for a great photo and an even better memory. We were definitely the most coordinated pew in the chapel that day.

{% for photo in site.data["photos-20250413"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}