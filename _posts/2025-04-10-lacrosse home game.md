---
layout: base
title: "Lacrosse - Another home game"
date: 2025-04-10
---

This afternoon we headed out to another one of Rieke’s lacrosse games. The weather was warm and sunny — perfect for cheering from the sidelines. It’s been so fun watching her grow into the sport. She’s found her place on defense, using her height and quick reflexes to hold the line, and it’s clear she’s become a real asset to the team.

Unfortunately, they didn’t come away with a win this time. The team played hard and kept the energy up, but the scoreboard just didn’t swing their way. Still, Rieke played with heart, and we were proud to be there supporting her. Win or lose, she’s all in — and that’s what matters.

{% for photo in site.data["photos-20250410"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}