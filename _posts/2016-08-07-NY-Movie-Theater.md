---
published: true
layout: post
type: painting
origin: American
year: 1939
artist_id: hopper_edward
images:
  url: http://www.edwardhopper.net/images/paintings/newyork-movie.jpg
---

test

<div class ="main-image">
{% for image in page.images %}
<img src="{{ site.baseurl }}{{ image.url }}" class="">
<br>
<hr>
<br>
{% endfor %}
</div>

One of the things that strikes me about Hoppers paintings is their lack of corporate fingerprints. It's as if the logos, slogans, and commercialism that litters our visual landscape has been erased, leaving us to witness and know their effects.

<hr>