---
layout: base
title: "A Grinchy Christmas Surprise"
date: 2024-12-23
---

Christmas morning started with a surprise no one expected — the presents were gone, and the Grinch was under the tree. Literally. I decided to shake things up this year and dressed up as the Grinch himself, sneaking out early to hide all the gifts before anyone woke up. When the family came downstairs, there I was — green face, Santa coat, and a mischievous grin — curled up beneath the tree like I had just finished my holiday heist.

Once the laughter (and confusion) settled, the kids and Rieke followed clues through a scavenger hunt to find where the “stolen” presents were hidden. It added an extra layer of fun and chaos to the morning, and Rieke loved every second of it — especially since this was her first and only Christmas in the U.S. After the hunt, we settled into our traditional Christmas morning routine: digging through stockings, unwrapping presents, and soaking in the joy (and mess) of the day. It was silly, special, and full of love — everything Christmas should be.

{% for photo in site.data["photos-20241225"] %}
  <div>
    <img src="{{ site.baseurl }}/photos/{{ photo.file }}" alt="{{ photo.caption }}">
    <p>{{ photo.caption }}</p>
  </div>
{% endfor %}