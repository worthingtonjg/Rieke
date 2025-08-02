---
layout: base
title: "Road Trip to the California Coast"
date: 2025-03-30
---

Our next big adventure took us back down to Minden, Nevada — a familiar stop, where we spent one night at Jana’s dad’s house. The next morning, we packed up and hit the road again, this time in his RV, heading toward the California coast. Our destination: the KOA campground near Santa Cruz and Monterey Bay.

The RV park was huge — the kind of place that felt more like a little resort than a campground. There was a swimming pool, a giant bounce pad, and plenty of space to explore. Even though the weather stayed cloudy and overcast, Rieke practically lived at the pool. She didn’t let the lack of sunshine stop her one bit. Molly, on the other hand, found her happy place on the bounce pad, jumping for what felt like hours. It was one of those laid-back, make-your-own-fun kind of days — just the kind of start we needed for our coastal adventure.

{% for photo in site.data["photos-20250330"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}