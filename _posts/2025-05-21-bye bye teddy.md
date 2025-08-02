---
layout: base
title: "Bye Bye Teddy"
date: 2025-05-21
---

As Rieke’s time with us comes to a close, the goodbyes are starting — and today was one of the tough ones. She spent the afternoon visiting her best friend Addie one last time. The two of them have shared so much this year — inside jokes, late-night chats, school dances, and more shopping trips than we could count.

But this goodbye wasn’t just to Addie — it was also to Teddy, Addie’s adorable dog, who Rieke absolutely adored. One of the last photos we snapped was of her holding Teddy close, not quite ready to let go. It was a quiet, sweet moment — one of many that will stay with her long after she’s back home.

{% for photo in site.data["photos-20250521"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}