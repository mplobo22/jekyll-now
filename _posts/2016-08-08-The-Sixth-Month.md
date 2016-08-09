---
published: true
layout: post
type: drawing
origin: Japanese
year: About 1783
artists:
  - url: /artists/Kiyonaga_Torii.md
images:
  - url: https://data.ukiyo-e.org/mfa/images/sc160945.jpg
---

<div class ="main-image">
{% for image in page.images %}
<img src="{{ site.baseurl }}{{ image.url }}" class="">
<br>
<hr>
<br>
{% endfor %}
</div>

In one of Kiyonaga's most iconic images, revelers enjoying the summer weather drink sake and gaze out on the water. We see one woman from behind leaning on the railing and striking a distinctive pose.

<hr>


<div class="artist-info">
{% for artist in site.artists %}
<a href="{{ site.baseurl }}{{ site.artists.url }}"><h2>{{ artist.name }}</h2></a>
<p>{{ artist.dates }}</p>
<p><span>MOVEMENT:</span>{{ artist.movement }}</p>
<p><span>WEBSITE:</span>{{ artist.website }}</p>
<p><span>BIO:</span>{{ artist.bio }}</p>
<hr>
{% endfor %}

  </div>