---
layout: base
title: "Cookies, Cookies, and More Cookies"
date: 2024-12-12
---

By December, we had learned a few things about Rieke — she loves shopping, she loves makeup, but above all else… she really loves cookies. If she’s not eating them, she’s making them. And if she’s doing both at the same time, well, that’s pretty much her version of the perfect day.

Today, she and Jana spent the afternoon in the kitchen baking chocolate-dipped gingerbread cookies — festive little treats to share with our ward and deliver to neighbors. The house smelled amazing, and the kitchen was full of flour, laughter, and a lot of “taste-testing.” Let’s just say we’re pretty sure not all the cookies made it into the gift bags. Watching Rieke roll dough and dip cookies like a seasoned pro, it was clear this was her happy place — and we weren’t complaining. She might just bake her way through the entire holiday season.

{% for photo in site.data["photos-20241212"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}