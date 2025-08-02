---
layout: base
title: "Fire Fighter Breakfast"
date: 2025-05-26
---

This morning marked our very last activity with Rieke before she heads back to Germany — and it couldn’t have been more fitting. The Santaquin Fire Department was hosting a charity breakfast, and knowing Rieke’s love for all things fire-related, we made sure it was on the calendar. In Germany, her family volunteers with the local fire department, so anything with fire trucks and gear is right up her alley.

We had breakfast inside the firehouse, surrounded by engines, hoses, and gear — and Rieke was absolutely in her element. She lit up the moment we stepped inside. But the best part came when the fire chief found out she was from Germany and part of a volunteer firefighter family. He went above and beyond, gifting her a special set of Santaquin Fire t-shirts — one for her and one for each member of her family back home. It was such a thoughtful gesture, and the perfect final souvenir for her time here.

{% for photo in site.data["photos-20250526"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}