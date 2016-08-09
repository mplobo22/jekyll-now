---
published: true
layout: post
type: painting
origin: American
year: 1939
artists:
  - url: /artists/Hopper_Edward.md
images:
  - url: http://www.edwardhopper.net/images/paintings/newyork-movie.jpg
---

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


<div class="artist-info">
{% for artist in site.artists %}
<a href="{{ site.baseurl }}{{ artists.url }}"><h2>{{ artist.name }}</h2></a>
<p>{{ artist.dates }}</p>
<p><span>MOVEMENT:</span>{{ artist.movement }}</p>
<p><span>WEBSITE:</span>{{ artist.website }}</p>
<p><span>BIO:</span>{{ artist.bio }}</p>
<hr>
{% endfor %}


  </div>