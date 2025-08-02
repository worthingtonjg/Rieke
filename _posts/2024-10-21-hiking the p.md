---
layout: base
title: "Hiking the Payson P"
date: 2024-10-21
---

One of Utah’s stranger but endearing traditions is putting giant letters on the sides of mountains to represent local high schools and universities. Most people know about the big white “Y” on the mountain above BYU in Provo, but closer to home, Payson has its own version — the “P.”

Today, Jana took Rieke to hike up to the “P” on the mountain overlooking Payson. It’s a steep trail, but the views are totally worth it. From the top, you can see the whole valley stretched out below — farms, towns, and the golden colors of fall creeping across the landscape. It’s one of those hikes that gives you a sense of place, and for Rieke, a cool glimpse into a quirky piece of Utah culture she might never have seen otherwise.

{% for photo in site.data["photos-20241021"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}